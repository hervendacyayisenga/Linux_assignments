# Assignment 1 – Introduction to Linux Basic Commands

**Name**: Ndacyayisenga Herve
**Student ID**: 24768

## Part 1: GitHub Commands & Outputs

### 1. Repository Access
**Command Used:**
```bash
git clone https://github.com/eliekayitare/Linux_sem2_A.git
cd Linux_sem2_A
```

**Output Screenshot (Simulated Terminal Output):**
```text
Cloning into 'Linux_sem2_A'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```

### 2. Branch Naming
**Command Used:**
```bash
git checkout -b 24768_ndacyayisenga_herve_assignment1
```

**Output Screenshot (Simulated Terminal Output):**
```text
Switched to a new branch '24768_ndacyayisenga_herve_assignment1'
```

### 3. Pushing Your Work
**Command Used:**
```bash
git push -u origin 24768_ndacyayisenga_herve_assignment1
```

**Output Screenshot (Simulated Terminal Output):**
```text
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.2 KiB | 1.20 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/eliekayitare/Linux_sem2_A.git
 * [new branch]      24768_ndacyayisenga_herve_assignment1 -> 24768_ndacyayisenga_herve_assignment1
Branch '24768_ndacyayisenga_herve_assignment1' set up to track remote branch '24768_ndacyayisenga_herve_assignment1' from 'origin'.
```

---

## Part 2: Path & Commands Practice (Using login directory: `mac`)

*Note: The root structure translates to `/home/mac/Practice/...` based on the assignment instructions.*

### Question 1
**If you are in the P3 directory, write the command to go to your home.**
1. Using a relative path:
   ```bash
   cd ../../..
   ```
2. Using an absolute path:
   ```bash
   cd /home/mac
   ```

### Question 2
**Write the command to show a long listing of `Here`.**
1. Using a relative path if you are in the `Command` directory:
   ```bash
   ls -l ../P1/P3/Here
   ```
2. Using an absolute path:
   ```bash
   ls -l /home/mac/Practice/P1/P3/Here
   ```

### Question 3
**Write the command to copy the directory `P3` to the `Command` directory.**
1. Using a relative path if you are in the `P2` directory:
   ```bash
   cp -r ../P3 ../../Command
   ```
2. Using a relative path if you are in the `P3` directory:
   ```bash
   cp -r ../P3 ../../Command
   ```
3. Using a relative path if you are in the `Command` directory:
   ```bash
   cp -r ../P1/P3 .
   ```
4. Using an absolute path:
   ```bash
   cp -r /home/mac/Practice/P1/P3 /home/mac/Practice/Command
   ```

### Question 4
**Write the command to copy the files in `P3` to the `Command` directory.**
1. Using a relative path if you are in the `P2` directory:
   ```bash
   cp -r ../P3/* ../../Command/
   ```
2. Using a relative path if you are in the `P3` directory:
   ```bash
   cp -r * ../../Command/
   ```
3. Using a relative path if you are in the `Command` directory:
   ```bash
   cp -r ../P1/P3/* .
   ```
4. Using an absolute path:
   ```bash
   cp -r /home/mac/Practice/P1/P3/* /home/mac/Practice/Command/
   ```

### Question 5
**What's the difference between these last 2 (Questions 3 and 4)?**
- **Question 3** copies the entire `P3` directory structure itself (creating a `P3` folder inside `Command`).
- **Question 4** copies only the contents (the files and subdirectories) inside the `P3` directory directly into the `Command` directory without nesting them under a newly created `P3` folder.

### Question 6
**What do you think the yellow color means? The blue? What color should hereWeAre be, and why?**
- **Blue**: Represents directories (folders).
- **Yellow**: Represents regular files.
- **Color for `hereWeAre`**: It should be **Yellow**. Because the standard representation in the diagram implies that leaves which aren't explicitly marked as blue (empty directories) are files. Since `hereWeAre` is an endpoint in the tree like `info` and `Hello`, it represents a file and therefore belongs to the yellow category.
