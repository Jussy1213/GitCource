：git diff
3.查看提交历史：git log/git log --pretty=oneline(格式整齐)
  回退历史版本：git reset --hard HEAD^( HEAD^^、HEAD^^^)
  使用commit_id还原版本：git reset --hard f285052[commit_id的前几位]
  [HEAD指向的版本就是当前版本，因此Git允许我们在版本之间穿梭，使用命令给git reset --hard commit_id
   穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本
   要重返未来，用git relog查看命令历史，以便确定要回到未来的哪个版本]
4.git分为暂存区和工作区：git add把修改的文件提交到暂存区，git commit最后一次性提交到分支
5.撤销修改：