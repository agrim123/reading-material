# find

> search for files in a directory hierarchy

## Basic syntax

```bash
$ find [OPTIONS..] [path...] [expression]
```

##### Basic Examples

```bash
$ find -name "query"   # case sensitive
$ find -iname "query"  # ignore the case of the query
$ find -not -name "not_query"  # avoid a query
```

##### Finding By File types

```bash
$ find -type [descriptor] [query]
```

Basic descriptors:

- f: regular file
- d: directory
- l: symbolic link
- c: character devices
- b: block devices

## Options

| Options          | Use                                          |
| ---------------- |:--------------------------------------------:| 
| -name [pattern]  | Base of file name matches shell pattern. The  metacharacters (`*`,  `?`,  and  `[]`\) match a `.` at the start of the base name.                                |
| -i               | ignore case                                  |
| -type            | type of file (f\|d\|l\|c\|b\)                |
| -size            | filter by size (c\|k\|M\|G\|b\)              |
| -perm            | filter by permissions                        |
| -L               | Follow symbolic links                        |
