# Ubuntu Command Cheatsheet (Daily Use)

## 📁 Navigation
pwd                     # show current directory
ls                      # list files
ls -la                  # detailed list
cd folder_name          # go into folder
cd ..                   # go up one level
cd ~                    # go to home directory

## 📂 File & Folder Management
mkdir folder             # create folder
mkdir -p a/b/c           # nested folders
rm file.txt              # delete file
rm -r folder             # delete folder
rm -rf folder            # force delete (danger)
cp a.txt b.txt           # copy file
mv a.txt b.txt           # rename / move

## 📄 File Viewing & Editing
cat file.txt             # view file
less file.txt            # scroll view
nano file.txt            # edit file
touch file.txt           # create empty file

## 🔍 Search
find . -name "*.md"      # find files
grep "text" file.txt     # search text in file

## 📦 Package Management
sudo apt update
sudo apt install git -y
sudo apt remove pkg

## 🔧 System Info
df -h                    # disk usage
free -h                  # memory usage
top                      # running processes
ps aux                   # process list

## 🔑 Permissions
chmod 755 file.sh        # change permissions
chown user:group file    # change owner

## 🌐 Networking
ip a                     # IP info
ping google.com
curl https://example.com

## 🐳 Docker (basic)
docker ps
docker images
docker build -t app .
docker run -p 8080:80 app

## 🔁 Git (daily)
git status
git pull
git add .
git commit -m "message"
git push

