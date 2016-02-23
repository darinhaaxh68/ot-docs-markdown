# SUMMARY

-   [DITA Open Toolkit 2.2](index.md)
-   [Release Notes](release-notes/index.md)
-   [Getting Started](getting-started/index.md)
    -   [Installing the toolkit](getting-started/installing-client.md)
    -   [Building output using the dita command](getting-started/first-build-using-dita-command.md)
-   [User Guide](user-guide/index.md)
    -   [DITA Open Toolkit Overview](user-guide/overview-of-dita-ot.md)
        -   [DITA specification support](user-guide/DITA_spec-support.md)
            -   [DITA 1.2 support](user-guide/DITA_v1-2-support.md)
            -   [DITA 1.3 support](user-guide/DITA_v1-3-support.md)
        -   [Tested platforms and tools](user-guide/tested-tools.md)
    -   [Installing the DITA-OT](user-guide/installing.md)
        -   [Prerequisite software](user-guide/prerequisite-software.md)
        -   [Installing the toolkit](user-guide/installing-client.md)
    -   [Publishing DITA content](user-guide/transforming-dita-content.md)
        -   [Building output using the dita command](user-guide/build-using-dita-command.md)
        -   [Publishing DITA content from Ant](user-guide/publishing-with-ant.md)
            -   [Ant](user-guide/ant.md)
            -   [Building output using Ant](user-guide/building-with-ant.md)
            -   [Creating an Ant build script](user-guide/creating-an-ant-build-script.md)
    -   [Output formats](user-guide/AvailableTransforms.md)
        -   [DITA to DocBook](user-guide/dita2docbook.md)
        -   [DITA to Eclipse Content](user-guide/dita2eclipsecontent.md)
        -   [DITA to Eclipse help](user-guide/dita2eclipsehelp.md)
        -   [DITA to HTML5](user-guide/dita2html5.md)
        -   [DITA to HTML Help \(CHM\)](user-guide/dita2htmlhelp.md)
        -   [DITA to Java Help](user-guide/dita2javahelp.md)
        -   [DITA to ODT](user-guide/dita2odt.md)
        -   [DITA to PDF \(PDF2\)](user-guide/dita2pdf.md)
            -   [Creating Change Bars](user-guide/pdf2-creating-change-bars.md)
        -   [DITA to RTF](user-guide/dita2wordrtf.md)
        -   [DITA to TocJS](user-guide/dita2tocjs.md)
        -   [DITA to troff](user-guide/dita2troff.md)
        -   [DITA to XHTML](user-guide/dita2xhtml.md)
    -   [Extending the DITA-OT](user-guide/extending-the-dita-ot.md)
        -   [Installing plug-ins](user-guide/plugins-installing.md)
        -   [Removing plug-ins](user-guide/plugins-removing.md)
    -   [Globalizing DITA content](user-guide/DITA-globalization.md)
        -   [Globalization support](user-guide/globalization-supported-in-dita-ot.md)
        -   [Supported languages: HTML](user-guide/DITA-globalization-xhtml.md)
        -   [Supported languages: PDF](user-guide/DITA-globalization-pdf.md)
    -   [Troubleshooting](user-guide/troubleshooting-overview.md)
        -   [DITA-OT error messages](user-guide/DITA-messages.md)
        -   [Other error messages](user-guide/other-errors.md)
        -   [Log files](user-guide/log-files.md)
        -   [Accessing help for the dita command](user-guide/dita-command-help.md)
        -   [Checking the DITA-OT version](user-guide/determining-version-of-ditaot.md)
        -   [Enabling debug mode](user-guide/enabling-debug-mode.md)
        -   [Increasing Java memory allocation](user-guide/increasing-the-jvm.md)
        -   [Reducing processing time](user-guide/reducing-processing-time.md)
-   [Parameter Reference](parameters/index.md)
    -   [DITA-OT parameters](parameters/parameters_intro.md)
        -   [Common](parameters/parameters-base.md)
        -   [HTML-based output](parameters/parameters-base-html.md)
        -   [HTML5 and XHTML](parameters/parameters-common-html.md)
        -   [HTML5](parameters/parameters-html5.md)
        -   [Eclipse content](parameters/parameters-eclipsecontent.md)
        -   [Eclipse Help](parameters/parameters-eclipsehelp.md)
        -   [HTMLHelp](parameters/parameters-htmlhelp.md)
        -   [JavaHelp](parameters/parameters-javahelp.md)
        -   [Open Document Format](parameters/parameters-odt.md)
        -   [Other](parameters/parameters-other.md)
        -   [PDF](parameters/parameters-pdf.md)
    -   [DITA command arguments](parameters/dita-command-arguments.md)
    -   [Configuration properties](parameters/configuration-properties.md)
        -   [plugin.properties file](parameters/lib-plugin-properties.md)
        -   [configuration.properties file](parameters/lib-configuration-properties.md)
    -   [Internal Ant properties](parameters/internal-ant-properties.md)
-   [Developer Reference](dev_ref/index.md)
    -   [DITA-OT Architecture](dev_ref/DITA-OTArchitecture.md)
        -   [Processing structure](dev_ref/processing-structure.md)
        -   [Processing modules](dev_ref/processing-pipeline-modules.md)
        -   [Processing order](dev_ref/processing-order.md)
        -   [Pre-processing modules](dev_ref/DITA-OTPreprocess.md)
            -   [Generate lists \(gen-list\)](dev_ref/preprocess-genlist.md)
            -   [Debug and filter \(debug-filter\)](dev_ref/preprocess-debugfilter.md)
            -   [Resolve map references \(mapref\)](dev_ref/preprocess-mapref.md)
            -   [Copy related files \(copy-files\)](dev_ref/preprocess-copyfiles.md)
            -   [Resolve keyref \(keyref\)](dev_ref/preprocess-keyref.md)
            -   [Conref push \(conrefpush\)](dev_ref/preprocess-conrefpush.md)
            -   [Conref \(conref\)](dev_ref/preprocess-conref.md)
            -   [Resolve code references \(coderef\)](dev_ref/preprocess-coderef.md)
            -   [Move metadata \(move-meta-entries\) and pull content into maps \(mappull\)](dev_ref/preprocess-metadata.md)
            -   [Chunk topics \(chunk\)](dev_ref/preprocess-chunk.md)
            -   [Map based linking \(maplink\)](dev_ref/preprocess-maplink.md)
            -   [Pull content into topics \(topicpull\)](dev_ref/preprocess-topicpull.md)
            -   [Flagging in the toolkit](dev_ref/preprocess-flagging.md)
        -   [HTML-based processing modules](dev_ref/XhtmlWithNavigation.md)
            -   [Common HTML-based processing](dev_ref/XhtmlCommon.md)
            -   [XHTML processing](dev_ref/XhtmlDefault.md)
            -   [HTML5 processing](dev_ref/html5.md)
            -   [Eclipse help processing](dev_ref/XhtmlEclipse.md)
            -   [TocJS processing](dev_ref/XhtmlTocjs.md)
            -   [HTML Help processing](dev_ref/XhtmlCHM.md)
            -   [JavaHelp processing](dev_ref/XhtmlJavahelp.md)
        -   [PDF processing modules](dev_ref/PdfDefault.md)
        -   [Open Document Format processing modules](dev_ref/OdtDefault.md)
    -   [Extending the DITA-OT](dev_ref/extending-the-ot.md)
        -   [Manually installing plug-ins](dev_ref/plugins-installing.md)
        -   [Manually removing plug-ins](dev_ref/plugins-removing.md)
        -   [Rebuilding the DITA-OT documentation](dev_ref/rebuilding-the-dita-ot-documentation.md)
    -   [Creating plug-ins](dev_ref/plugins-overview.md)
        -   [Plug-in configuration file](dev_ref/plugin-configfile.md)
        -   [Extending the XML Catalog](dev_ref/plugin-xmlcatalog.md)
        -   [Adding new targets to the Ant build process](dev_ref/plugin-anttarget.md)
        -   [Adding Ant targets to the pre-process pipeline](dev_ref/plugin-antpreprocess.md)
        -   [Integrating a new transformation type](dev_ref/plugin-newtranstype.md)
        -   [Override styles with XSLT](dev_ref/plugin-overridestyle.md)
        -   [Modifying or adding generated text](dev_ref/plugin-addgeneratedtext.md)
        -   [Passing parameters to existing XSLT steps](dev_ref/plugin-xsltparams.md)
        -   [Adding Java libraries to the classpath](dev_ref/plugin-javalib.md)
        -   [Adding diagnostic messages](dev_ref/plugin-messages.md)
        -   [Managing plug-in dependencies](dev_ref/plugin-dependencies.md)
        -   [Version and support information](dev_ref/plugin-support.md)
        -   [Creating a new plug-in extension point](dev_ref/plugin-newextensions.md)
        -   [Example plugin.xml file](dev_ref/plugin-sample.md)
    -   [Customizing PDF output](user-guide/dita2pdf-customization.md)
    -   [Migrating customizations](dev_ref/migration.md)
        -   [Migrating to Release 1.8](dev_ref/migrating-to-1.8.md)
        -   [Migrating to Release 1.7](dev_ref/migrating-to-1.7.md)
            -   [Flagging updates](dev_ref/flagging-migration.md)
        -   [Migrating to Release 1.6](dev_ref/migrating-to-1.6.md)
        -   [Migrating to Release 1.5.4](dev_ref/migrating-to-1.5.4.md)
    -   [Implementation dependent features](dev_ref/DITA1.2-implementation-dependent-features.md)
    -   [Extended functionality](dev_ref/extended-functionality.md)
-   [DITA Resources](user-guide/dita-and-dita-ot-resources.md)
    -   [Project website at dita-ot.org](http://www.dita-ot.org/)
    -   [Project page at dita.xml.org](http://dita.xml.org/wiki/the-dita-open-toolkit)
    -   [Yahoo! dita-users group](http://groups.yahoo.com/group/dita-users/)
    -   [DITA-OT Users Google Group](https://groups.google.com/d/forum/dita-ot-users)
    -   [DITA-OT Development Google Group](https://groups.google.com/d/forum/dita-ot-dev)
    -   [OASIS DITA Technical Committee](http://www.oasis-open.org/committees/dita/)
