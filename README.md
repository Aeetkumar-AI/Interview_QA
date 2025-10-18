# Interview_QA

# Git Bash Login and setup Github Account
```bash
git config --global user.name "NewUserName"
```

```bash
git config --global user.email "newemail@example.com"
```

# Git Clone Repo
```bash
git clone https://github.com/Aeetkumar-AI/Interview_QA.git
```

```bash
cd INTERVIEW_QA
```

# Create Python Environment
```bash
conda create -n interviewQA python=3.13 -y
```

# To activate this environment, use       
```bash
conda activate interviewQA        
```

# To deactivate an active environment, use
```bash
conda deactivate
```

# Git Commands
```bash
git status      # track changes
```

```bash
git add .
```

```bash
git commit -m "Updated README.md file"
```

```bash
git push origin main
```

# Understand Manual Folder and File creation

# Understand How to create directly and file using code

```bash
os.mkdir(directoryname)
os.makedirs(os.path.dirname(filename), exist_ok=True)  # create parents
```

```bash
with open (filename, 'w') as f:
    f.write("Hello world\n")
```



