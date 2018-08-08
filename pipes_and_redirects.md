# Pipes and redirects

Corresponding videos:
- [Basics 04](https://www.youtube.com/watch?v=-Z5tCri-QlI)
- [Basics 05 - apt-get](https://www.youtube.com/watch?v=8P-Vek7Vtgg&t=535s)


## Linux Process Channels

Every command has 3 channels:

| Name | abbreviation | channel |
| :---: | :---: | :---: |
| Standard in    | STDIN  | 0 |
| Standard out   | STDOUT | 1 |´
| Standard error | STDERR | 2 |



## Pipe

```
# this is the pipe sign: |
# it takes STDOUT on the left side and turns it into STDIN on the right
```

## Redirect

```
# this is the redirect sign: >
# It writes STDOUT to a file, 
# If the file doesnt exist it creates it
# If the file exists it overrides it
echo "test" > test.file
# this is the same as above 
echo "test" 1> test.file
 
# If you dont want to override the file use >>
echo "test2" >> test.file

# If you want to write STDERR to a file use
ls -l nonexistentfile >> test.file

# takes a file and produces STDIN to funnel into an command
cat < test.file

```
