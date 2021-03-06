# Arguments and options for the dita command

The dita command takes mandatory arguments to process DITA content, manage plug-ins, or print information about the command. Options can be used to modify the command behavior or specify additional configuration parameters.

## Usage

 

>  `**dita** ` `**-i** ` *file* `**-f** ` *name* \[ *options* \]

 

>  `**dita** ` `**-install** ` \[ \{ *file* *| url* \} \]

 

>  `**dita** ` `**-uninstall** ` *id* 

 

>  `**dita** ` `**-help** ` 

 

>  `**dita** ` `**-version** ` 

## Arguments

 -i, -input file
 :   Specifies the master file for your documentation project. Typically this is a DITA map, however it also can be a DITA topic if you want to transform a single DITA file. The path can be absolute, relative to args.input.dir, or relative to the current directory if args.input.dir is not defined.

  -f, -format name
 :   Specifies the output format \(transformation type\).

  -install file
 -install url
 :   Install a single plug-in from a local ZIP file or from a URL.

  -install
 :   If no file or url argument is provided, the integration process reloads plug-ins from the plugins directory. This approach can be used to integrate mutltiple plug-ins at once.

  -uninstall id
 :   Uninstall a plug-in with the specified ID.

  -h, -help
 :   Print command usage help.

  -version
 :   Print version information and exit.

 ## Options

 -o, -output dir
 :   Specifies the path of the output directory; the path can be absolute or relative to the current directory. By default, the output is written to the out subdirectory of the current directory.

  -filter file
 :   Specifies a filter file to be used to include, exclude, or flag content.

  -t, -temp dir
 :   Specifies the location of the temporary directory.

  -v, -verbose
 :   Verbose logging.

  -d, -debug
 :   Debug logging.

  -l, -logfile file
 :   Write logging messages to a file.

  -Dproperty=value
 :   Specify a value for a parameter. Supported parameters are the same as Ant parameters and are transformation type specific.

  -propertyfile file
 :   Load all properties from a file. Properties specified with the -D option take precedence.

 **Related information**  


[DITA-OT parameters](parameters_intro.md)

