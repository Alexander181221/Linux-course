   1  sudo adduser user1

   2  sudo useradd -s /bin/bash -m -d /home/user2 user2 

   3  tail /etc/passwd

   4  tail /etc/group

   5  sudo tail /etc/shadow

   6  sudo userdel user1 -r

   7  tail /etc/passwd

   8  sudo addgroup hw3gp

   9  sudo usermod -aG hw3gp user2

   10  id user2 

   11  sudo gpasswd -d user2 hw3gp 

   12  sudo adduser user3 

   13  sudo usermod -aG sudo user3

   14  sudo su user3

   15  history

   16  sudo addgroup developer

   17  useradd --help

   18  sudo useradd -s /bin/bash -m -d /home/user_dev1 -G developer  user_dev1

   19  id user_dev1 

   20  sudo useradd -s /bin/bash -m -d /home/user_dev2 -G developer  user_dev2

   21  sudo useradd -s /bin/bash -m -d /home/user_dev3 -G developer  user_dev3

   23  mkdir dir_for_teamdev

   24  cd dir_for_teamdev/

   25  touch file1 file2 file3

   26  ll

   27 chmod g+x *

   28 sudo chown :developer f*

   29 sudo chmod g+s f* 

   30 mkdit new_dir

   31 touch f1 f2 f3 

   33 sudo chmod g+w .

   34 sudo chmod a+t .



