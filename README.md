<div id="Ad1" data-type="ad" data-publisher="" data-zone="ron" style="width: 300px; height: 250px; margin: 0px auto;" data-site="C-languagetranslator" data-format="300x250"> 
 
<script type='text/javascript'>
function _dmBootstrap(file) {
    var _dma = document.createElement('script');
    _dma.type = 'text/javascript';
    _dma.async = true;
    _dma.src = ('https:' == document.location.protocol ? 'https://' : 'http://') + file;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(_dma);
}
function _dmFollowup(file) { if (typeof DMAds === 'undefined') _dmBootstrap('cdn2.DeveloperMedia.com/a.min.js'); }
(function () { _dmBootstrap('cdn1.DeveloperMedia.com/a.min.js'); setTimeout(_dmFollowup, 2000); })();
</script>
</div>

<div class="wikidoc">
<p><strong>Visual Studio add-in/extension that generates code based on OO design patterns</strong><br>
<br>
This is a Visual Studio add-in/extension (for VS 2015 and 2017) that indexes some commonly known OO patterns, presents them in easy to search user interface and inserts the code into your working project.<br>
It provides you with parameters to further customize the patterns and<br>
it works for languages supported by Visual Studio like C#, VB.net, C&#43;&#43; flavors, F# etc.<br>
<br>
<strong>Project Description</strong><br>
This add-in has a specific version for each version of Visual Studio starting with 2008 and
<br>
it requires <a href="http://www.microsoft.com/downLoads/details.aspx?familyid=AB99342F-5D1A-413D-8319-81DA479AB0D7&displaylang=en">
Net 3.5 Service Pack1</a> or higher to run.<br>
The express versions of Visual Studio are unable to use this add in, but the premium or community editions could.</p>
<p><img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=vsdesignpatterns&DownloadId=1458833" alt="wizard" width="640" height="480"><br>
<br>
<br>
<strong>Quick guide about how to use this add-in </strong><br>
<br>
At a minimum, download the zipped version that matches your version of Visual Studio.<br>
You can download multiple versions if you have multiple versions of the IDE.<br>
<br>
It's best to close Visual Studio before the installation.<br>
Download the archive, unzip it, and look for the the folder(s) corresponding to <br>
the same Visual Studio version(s) you are using.<br>
<br>
You can install multiple versions if you have multiple versions of the IDE. An unistall link for its
<br>
respective version should show up under the <br>
<em>Start\DesignPattern\Uninstall Design Patterns for 20XX Windows</em> windows startup menu for add-ins.<br>
For the extensions in VS 2015 or 2017 you can uninstall it by navigating to the 'Tools'\'Extensions and updates..' menu.</p>
<p>I have tested it only on Windows XP 32 bit and Windows 7 64 bit so far.<br>
<br>
<strong>Usage </strong><br>
<br>
Open an existing project in Visual Studio.<br>
Right click on the working project and select <em>Add DesignPatterns...</em><br>
<br>
<img title="DesignPatterns.png" src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=vsdesignpatterns&DownloadId=1458880" alt="mnuContext" width="292" height="227"><br>
<br>
You can narrow down to the pattern you need by filtering the patterns using the combo boxes<br>
on the top right of the form. You can also reorder by clicking on the column headers of the grid<br>
on the bottom.<br>
Select one pattern and click <em>Next</em>.<br>
On this screen you can change the values of some parameters should you needed it (defaults are
<br>
valid, you can always refactor them later in the IDE).<br>
Select <em>Next</em> again and you have a chance to see how the code will look like.<br>
You can go back by clicking on the <em>Previous</em> button, or select <em>Generate</em> to insert the code files<br>
into the current Visual Studio project.<br>
<br>
Beside the context menu, this add-in can be invoked from other places in Visual Studio<br>
You can choose where to access it from by invoking the Configuration form:<br>
<br>
<img title="config.png" src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=vsdesignpatterns&DownloadId=771921" alt="config.png"><br>
<br>
If the bottom grid was too cluttered, you can also hide the columns you are not interested
<br>
in from the same form.<br>
<br>
If some languages are of no interest to you, you can remove their respective provider by unchecking it from the configuration tab.<br>
<br>
<img title="LangProviders.png" src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=vsdesignpatterns&DownloadId=1454894" alt="LangProviders.png" width="536" height="373"></p>
<p>Starting with version 1.94, an extra assembly is included on trial basis for the rest of the gang of four design patterns. Its&nbsp;premium providers&nbsp;can be excluded at installation time or in the runtime configuration.<br>
<br>
An online tutorial is available on <a href="http://www.youtube.com/watch?v=S4Ni_5ay8_M">
youtube</a>.</p>
<p>The configuration also allows for&nbsp;customizing&nbsp;the Online Search Menus in the checkboxes grid:</p>
<p><img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=vsdesignpatterns&DownloadId=1458879" alt="config" width="536" height="433"></p>
<p>The online search menu will show up as a Right-click in the relevant windows.</p>
<p><img src="http://download-codeplex.sec.s-msft.com/Download?ProjectName=vsdesignpatterns&DownloadId=1458884" alt="context menu" width="600" height="288"></p>
<p><br>
<a href="http://www.youtube.com/watch?v=S4Ni_5ay8_M">Or click here to launch youtube in this window.</a><br>
<br>
<strong>Developer Notes</strong><br>
<br>
So far the source code and the build scripts are provided for Visual Studio 2008, 2010, 2012, 2013 and 2015).<br>
You can build all the versions by starting buildAll.bat from the Misc folder.<br>
The templates for patterns are available in the TemplateLibrary.zip from any of the
<br>
C:\Program Files (x86)\Software Fantasies\DesignPatterns for VS 200XX folders after installation.
<br>
You should unzip it in the ..\DesignPatterns\Misc folder if you want to work on the templates.<br>
Should you want to get involved with this project, (code or templates for other patterns or languages)
<br>
don't hesitate to contact me on the current <a href="https://vsdesignpatterns.codeplex.com/discussions">
Discussion page</a>, or on the <a href="http://visualstudiogallery.msdn.microsoft.com/1bba637a-285f-4829-97d6-4fc00552120b">
Visual Studio Gallery site</a>.</p>
<p>More information about extending the add-in can be found on <a title="codeproject" href="http://www.codeproject.com/Articles/767200/Visual-Studio-Design-Patterns-add-in-extension" target="_blank">
codeproject</a>.<br>
<br>
You can help this project by <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3UNEYK64HSWTJ">
donating to the developer using PayPal</a>, &nbsp;indirectly by supporting <br>
the advertisers on this page, or better yet, by purchasing a license when the trial expires.</p>
</div><div class="ClearBoth"></div>
