#Scala Interpreter ImageJ Plugin

Author: Kota Miura [http:cmci.embl.de](http:cmci.embl.de)

Date: 20121114  v1.0.1

Some fixes were done.

+ plugins.config fixed with package namings
+ ImgLib1 imports were excluded, as it will be deprecated

Thanks to Johannes Schindelin for these suggestions.

+ Console outputs (such as println() outputs) redirected to the Interpreter screen.
+ VM argument is now set internally from the code.
+ Pre-imports are now done using IMain class dierctly.

Date: 20121112 v1.0.0

It works, but still things to do. 

Things to do:

+ (done) Console output is not really good. Examine IMain class so that the output becomes simplified. 
+ (done) VM argument to set the scala mode should be within the code. Currently, externally givien. 
+ (done) import of ImageJ classes should be done faster using IMain class. Difficulty is on how to use Seq[String] type argument for quitetImport method. 

