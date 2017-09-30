# pyonlinedict

## 1.Introduction

Pyonlinedict is a command-line online dictionary based on Python 2.7 that supports queries in 27 languages or sentences. It is easy to find meaning when we encounter words or sentences that are not words or sentences.

## 1.介绍

pyonlinedict是一个基于python 2.7开发的命令行在线字典，支持27种语言的字词或句子翻译查询，当我们遇到不会字词或句子时，可以通过它轻松查询意思。

## 2.Installation

git clone https://github.com/sunnyelf/pyonlinedict.git

cd pyonlinedict

tar -xzvf pyonlinedict-1.0.5.tar.gz

python setup.py install --record install_path.txt

## 2.安装

git clone https://github.com/sunnyelf/pyonlinedict.git

cd pyonlinedict

tar -xzvf pyonlinedict-1.0.5.tar.gz

python setup.py install --record install_path.txt

## 3.Usage

Usage: pyonlinedict [options]

 Options: 
 
  -h, --help          Show help message and exit
  
  -q, --query         The word or sentence to be queried(required parameters)
  
  -f, --from          The type of the input language(default setting:auto)
  
  -t, --to            The type of the output language(default setting:zh)
  
  -l, --list          List the supported language types
  
  -v, --version       Displays the current version number and author information

 Usages: 
 
  pyonlinedict -h
  
  pyonlinedict -l
  
  pyonlinedict -v
  
  pyonlinedict -q hello
  
  pyonlinedict -q hello -f en -t zh
  
  pyonlinedict -q 'Hello world!' -f en -t zh

## 4.用法

用法：pyonlinedict [选项]

  选项：
   -h，--help         显示帮助消息并退出
   
   -q，--query        要查询的字或句子（必需的参数）
   
   -f，--from         输入语言的类型（默认设置：auto）
   
   -t，--to           输出语言的类型（默认设置：zh）
   
   -l，--list         列出支持的语言类型
   
   -v，-version       显示当前版本号和作者信息

  用例：
  
   pyonlinedict -h
   
   pyonlinedict -l
   
   pyonlinedict -v
   
   pyonlinedict -q hello
   
   pyonlinedict -q hello -f en -t zh
   
   pyonlinedict -q 'hello world' -f en -t zh

## 5.Uninstall

cat install_path.txt | xargs rm -rf

## 5.卸载

cat install_path.txt | xargs rm -rf
