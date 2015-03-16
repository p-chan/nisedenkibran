NiseDenkiBran
====

![NISE DENKI BRAN](http://i.imgur.com/LuCaEd2.jpg)

LEMRN stack Vagrant box.  
Linux, Enginx(Nginx), MySQL, Ruby, Node.js stack.

## Feature
Name | Version | Notes
--- | --- | ---
CentOS | v6.5 | Based chef/cent-6.5
Nginx | v1.6.2 | 
Ruby | v2.2.1 | Installed by rbenv
Node.js | v0.12.0 | Installed by nodebrew
MySQL | v5.6.23 | 
Git | v2.3.3 | 
Vim | v7.4.20 | 

## Usage

### 1. Install Vagrant and VirtualBox

- [Vagrant](https://www.vagrantup.com/downloads.html)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

### 2. Clone the NiseDenkiBran Github Repository
```
git clone https://github.com/p1ch-jp/nisedenkibran.git myapp
cd myapp
```

### 3. Vagrant Up
```
vagrant up
```

### 4. Access 192.168.33.10
![192.168.33.10](http://i.imgur.com/ODfS59g.png)

### 5. Happy Development
```
ﾊﾞﾝﾊﾞﾝﾊﾞﾝﾊﾞﾝﾊﾞﾝﾊﾞﾝﾊﾞﾝ
ﾊﾞﾝ　　　　 ﾊﾞﾝﾊﾞﾝﾊﾞﾝ
ﾊﾞﾝ (∩`･ω･)　ﾊﾞﾝﾊﾞﾝ
　＿/_ﾐつ/￣￣￣/
　　　＼/＿＿＿/￣￣
```

## Server Config
Key | Value
--- | ---
SSH Host | 192.168.33.10
SSH User | vagrant
SSH Pass | vagrant
DB Name | nisedenkibran
DB User | root
DB Pass | root
DB Host | localhost

## Author

[p1ch_jp](https://twitter.com/p1ch_jp)
