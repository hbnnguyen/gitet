# Gitlet
A Version Control System similar to Git for storing file backups.

## Getting started
Compile all Java classes:
```
javac gitlet/Main.java gitlet/Blob.java gitlet/Commit.java gitlet/CommitData.java gitlet/FileData.java gitlet/GitletException.java gitlet/Repository.java gitlet/Utils.java
```

## How to use Gitlet
Create a Gitlet repository:
```
java gitlet.Main init
```

Add a file:
```
java gitlet.Main add [file name]
```

Make a commit:
```
java gitlet.Main commit [commit message]
```

Remove a file:
```
java gitlet.Main rm [file name]
```

Print commit history:
```
java gitlet.Main log
```

Print global commit history:
```
java gitlet.Main global-log
```

Find a commit that contains a given message:
```
java gitlet.Main [commit message]
```

Print status:
```
java gitlet.Main status
```

Checkout a file:
```
java gitlet.Main checkout -- [file name]
```

Checkout a file from a specific commit:
```
java gitlet.Main [commit ID] -- [file name]
```

Checkout a branch:
```
java gitlet.Main [branch name]
```

Create a branch:
```
java gitlet.Main branch [branch name]
```

Remove a branch:
```
java gitlet.Main rm-branch [branch name]
```

Reset to a commit:
```
java gitlet.Main reset [commit ID]
```

Merge file from given branch to current branch:
```
java gitlet.Main merge [branch name]
```
