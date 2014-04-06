![gwsaospfieddoclava_sample](https://github.com/shareme/GWSAOSPifiedDocLava/raw/master/sampleimages/gwsaospifieddoclava.png)


GWSAOSPifiedDocLava
---


This is from the AOSP version of DocLava that uses antlr parsing to parse java 
code to produce javadocs. Its originally from the 4.4.2_r2 master branch.

THIS IS NOT ASSOCIATED WITH GOOGLE, AOSP, OR OHA.

# Eclipse Notes

Compliance Compiler Level set to 1.6 on project settings
tools.jar is imported as external jar on build path,see .classpath file

# Implementation Notes

Left off test stuff as AOSP team already tests and we just need the jar to 
use the doclet.

# Usage

To customize the templates you will start out with what is in the 
sample_template_dir and customize waht is at the root level to change 
the look,etc. See DocLava project at CodeGoogle for directions.

[DocLAva wiki list](https://code.google.com/p/doclava/w/list)



# Version

From 4.4.2_r2 AOSP master branch of doclava..ie platform/external/doclava

# Credit

AOSP team and Google and the OHA partners.

# License

Apache 2.0 License
