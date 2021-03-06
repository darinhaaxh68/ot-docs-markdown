# Building output using the dita command

DITA-OT includes a dita command-line tool. You can invoke the DITA-OT from the command-line tool and generate output.

The DITA-OT client is a command-line tool, there is no graphic user interface.

1.   Open a terminal window by typing the following in the search bar: 
    -   On OS X and Linux, type Terminal.
    -   On Windows, type Command Prompt.
2.   At the command-line prompt, enter the following command: 

    ```
    install-dir/bin/dita -i input-file -f format -o output-dir
    ```

    ```
    install-dir/bin/dita -i input-file -f format -Dparameter-name=value -o output-dir
    ```

    where:

    -   install-dir is the DITA-OT installation directory path.
    -   input-file is the DITA map or DITA file that you want to process.
    -   format is the output format \(transformation type\).
    -   output-dir is the output directory path for generated output.
    -   install-dir is the DITA-OT installation directory path.
    -   input-file is the DITA map or DITA file that you want to process.
    -   format is the output format \(transformation type\).
    -   parameter-name is the name of an optional parameter.
    -   value is an applicable value for the optional parameter.
    -   output-dir is the output directory path for generated output.
    If processing is successful, nothing is printed in the terminal window.

    If you do not specify an output directory, the dita command writes output to the out subdirectory of the current directory.

    **Tip:** If you add the absolute path for the DITA-OT install-dir/bin directory to the PATH environment variable, you can run the dita command from any location on the file system.


The following command generates HTML5 output for the sequence.ditamap file and writes the output to the test directory:

```
dita -i samples/sequence.ditamap -f html5 -o test
```

If the dita command is not on your PATH, use the following command:

```
install-dir/bin/dita i samples/sequence.ditamap -f html5 -o test
```

**Related information**  


[Arguments and options for the dita command](../parameters/dita-command-arguments.md)

