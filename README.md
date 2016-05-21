# ImageProcessor

I have made a commandline application in C# called ImageProcessor (should be preprocessor), this is the tool which will first process my image datasets,
for some machine learning experiments.
I want to release this tool as something useful in the future, its still a work in progress and has many TODOs.

ImageProcessor is a really cool program (in my humble opionion, Im a nerd) but I developed it very quickly which means its probably quite unstable and prone to crashing. If bugs are found please add an issue on GitHub, that would be much appreciated. Versions after 0.1 are meant for release. 0.1 is only meant to be used for a very specific machine learning project I am working on - which has a strict deadline.

A lot of rework is required and will be done in time.

These exist but do slightly different things
https://github.com/JimBobSquarePants/ImageProcessor
https://github.com/mattchoinski/ImageProcessor

##TODOS:
#ImageProcessor:
	- perhaps clustering for images
	- feature detection
	- direct memory interfacing so no need for using hdd if you dont want to
	- GUI
	- tons of bug fixes
	- make the code cleaner
	- get rid of the todos which litter the code base, put them here or do them!!!
	- move actual algorithm to class library so it can be seamlessly integrated into future projects
	- Add abilit to remove only one channel of colour
Used some StackOverflow help:
Also: http://www.codeproject.com/Articles/33838/Image-Processing-using-C
and: http://www.codeproject.com/Articles/9727/Image-Processing-Lab-in-C

TODO: rename since http://www.hanselman.com/blog/NuGetPackageOfTheWeekImageProcessorLightweightImageManipulationInC.aspx exists
TODO: Make into class library
TODO: Make Unit TestsReally good sources, for the raw image processing stuff
TODO: Convert all messages to a correct config structure
TODO: Global vars for things
TODO: add ascii options ie row/column, for now using row
TODO: ascii include A from RGBA ie allow transparency
TODO: Make a random destruction option either dark or light
TODO: open folder of images
TODO: allow merge to convert as well - not in first version
TODO: add crop functionality
TODO: add scaling functionality in convert
TODO: add more file formats
TODO: convert from ASCII
TODO: add filters
TODO: add inversion of colours -simple enough
TODO: proper error messages
TODO: reflections
TODO: rotations
TODO: Batch processing
TODO: Pixel destruction
TODO: noise addition gauss, poisson etc...
TODO: batch script i.e run convert and scale
TODO: refactor code
TODO: refactor how args are processed
TODO: rgb rbg have a thing which converts all possible inputs into readable form
TODO: weka support
TODO: scripting language for filters and using multiple arguments with file or batch
TODO: csv, JSON ouput Also make csv work with ascii checks

TODO: http://stackoverflow.com/questions/568968/does-any-one-know-of-a-faster-method-to-do-string-split
TODO: http://stackoverflow.com/questions/399798/memory-efficiency-and-performance-of-string-replace-net-framework/400065#400065

TODO: data4node migration of techniques used here

TODO: add this
graphics.CompositingQuality = System.Drawing.Drawing2D.CompositingQuality.HighQuality;
     graphics.InterpolationMode = System.Drawing.Drawing2D.InterpolationMode.HighQualityBicubic;
     graphics.SmoothingMode = System.Drawing.Drawing2D.SmoothingMode.HighQuality;

TODO: fix scaling batch cropping issue
TODO: check image memory cleanup

TODO: Blurs
TODO: Edge Detection
TODO: effects
TODO: GUI
TODO: Linux Support
TODO: Filters
TODO: sharpening
TODO: difference selection
TODO: comparators
TODO: Aliasing
TODO: Interpolation techniques

TODO: RGB / RGBA problem

TODO: GPU acceleration

TODO: add neural network processing (to be used with other libraries in dev)
TODO: documentation


ASCII Channels will always be stored per column/row (depeneding on future updates to code) in the RGBA way
i.e. rg (or gr) will have red channel first then green or RA will be red then alpha
