# cmps101-pt.u19/pa2

The following is a set of performance tests to run on your Sparse program. It takes five example input files and compares your results to our correct model outputs. It also includes a testing client for your List and Matrix ADT's as per the requirements of PA2. We have made this available to you to check your work before making your final submission.

## Installation

Run the following in your working directory (the directory you wrote your code in) to get the test script and example input files:

```bash
curl https://raw.githubusercontent.com/houi-lin/cmps101-pt.u19.grading/master/pa2/pa2.sh > pa2.sh
chmod +x pa2.sh
```

## Usage

After installation, you can run the script with this line:

```bash
./pa2.sh
```

It will print out the difference between your output and the correct output, using the `diff` command. Lack of any output between the set of "==========" means that your program is running correctly.

Any lines prefixed with `-` are from your own output, and are incorrect. Any lines prefixed with `+` are from the correct output, and are missing in your output.

## Removal

The following command will remove all text files and shell scripts in your directory. Since you should not have any files that end in `.txt` or `.sh` anyway, this should serve to delete all the files we gave you.

```bash
rm -f *.txt *.sh
```
