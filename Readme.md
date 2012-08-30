# MonoTouch for Visual Studio 2012

## About
The vs2012 branch contains a modified version of the [VsMonoTouch extension](https://github.com/follesoe/VSMonoTouch) that runs on Visual Studio 2012.

Actually, the current status is ["Works on My Machine"](http://www.codinghorror.com/blog/2007/03/the-works-on-my-machine-certification-program.html), because I needed a (particulary) quick and dirty solution.<br/>
Just feel free to apply any changes if reguired to make it works on your machine :)

Just go to the page of the original extension for further information: [https://github.com/follesoe/VSMonoTouch](https://github.com/follesoe/VSMonoTouch)

## Notes
After opening for the first time a MonoTouch solution in Visual Studio 2012, it could change the number of the version of the solution. If this happens, MonoDevelope could have problems opening again the solution. In this situation, just restore the previous number in the first lines of the .sln file with this values:

<pre>
Microsoft Visual Studio Solution File, Format Version 11.00
#Visual Studio 2010
</pre>