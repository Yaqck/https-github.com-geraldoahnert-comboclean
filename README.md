
<p align="center">
	<img align="center" src="https://user-images.githubusercontent.com/41551840/82152527-37348200-9838-11ea-96b4-5749348a9d3e.png">
</p>

<p align="center">
	<h3 align="center">Combo Clean</h3>
</p>

<p align="center">
	<a target="__blank" href="#">
	  <img src="https://img.shields.io/badge/status-finish-green?&style=for-the-badge"/>
	  <img src="https://img.shields.io/badge/license-mit-blue?&style=for-the-badge"/>
	</a>
</p>


<br>

<h2>About</h2>
<p>Use comboclean to make it easy to use email and passwords, from big combolists, in your script.</p>


<h2>Install</h2>

```markdown
$ git clone https://github.com/geraldoahnert/comboclean
$ cd comboclean/
$ chmod +x comboclean

# Install global command
$ sudo cp comboclean /usr/bin/comboclean
```

<h2>How to use</h2>

```markdown
# Local
$ ./comboclean --help

# Global
$ comboclean --help
```

<h2>Example</h2>

A combolist example:

```console
$ cat combolist.txt

username:password something | something | something
username:password something | something | something
username:password something | something | something
username:password something | something | something
username:password something | something | something
username:password something | something | something
```

Using <b>comboclean</b>

```console
$ comboclean -f combolist.txt -o combolist2.txt
```

```console
$ cat combolist2.txt

username:password
username:password
username:password
username:password
username:password
username:password
```
