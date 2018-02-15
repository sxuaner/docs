##################### .classpath####################
Class path can be created by using gradle.

Standard one looks like following:

<?xml version="1.0" encoding="UTF-8"?>
<classpath>
	<classpathentry kind="src" output="bin/main" path="src/main/java">
		<attributes>
			<attribute name="gradle_scope" value="main"/>
			<attribute name="gradle_used_by_scope" value="main,test"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="src" output="bin/test" path="src/test/java">
		<attributes>
			<attribute name="gradle_scope" value="test"/>
			<attribute name="gradle_used_by_scope" value="test"/>
		</attributes>
	</classpathentry>
	<classpathentry kind="con" path="org.eclipse.jdt.launching.JRE_CONTAINER/org.eclipse.jdt.internal.debug.ui.launcher.StandardVMType/JavaSE-1.8/"/>
	<classpathentry kind="con" path="org.eclipse.buildship.core.gradleclasspathcontainer"/>
	<classpathentry kind="output" path="bin/default"/>
</classpath>


To add an entry
<class>
	<classpathentry kind="lib" path="/usr/share/java/mysql-connnector.jar"/>
</class>

##################### .vscode/launch.JSON ####################

JSON format:
[{ "name":"value",
   "name2":"value2"}
]

console - what kind of console to use, for example, internalConsole, integratedTerminal, externalTerminal.

internal console cannot accept input stream.



    /* The following attributes are mandatory for every launch configuration:

        type - the type of debugger to use for this launch configuration. Every installed debug extension introduces a type, for example, node for the built-in node debugger, or php and go for the PHP and Go extensions.
        request - the request type of this launch configuration. Currently supported are launch and attach.
        name - friendly name which appears in the Debug launch configuration dropdown.

    Here are some optional attributes available to all launch configurations:

        preLaunchTask - to launch a task before the start of a debug session, set this attribute to the name of a task specified in tasks.json (located under the workspace's .vscode folder).
        internalConsoleOptions - control visibility of the Debug Console panel during a debugging session
        debugServer - for debug extension authors only: connect to the specified port instead of launching the debug adapter

    Many debuggers support some of the following attributes:

        program - executable or file to run when launching the debugger
        args - arguments passed to the program to debug
        env - environment variables (the value null can be used to "undefine" a variable)
        cwd - current working directory for finding dependencies and other files
        port - port when attaching to a running process
        stopOnEntry - break immediately when the program launches
        console - what kind of console to use, for example, internalConsole, integratedTerminal, externalTerminal.


    */


##################### .classpath####################