Hello! Please know that the PDF version of this file is outdated. Somehow, my code broke and Knit will no longer work. 
The PS1_REAL_FINAL.Rmd is the code that should work 100% fine. It just won't knit for some reason. The in this repo
will work, but it is a lower quality version I did earlier. The error I got when trying to knit is:
Error in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]) : 
  namespace 'xfun' 0.47 is being loaded, but >= 0.48 is required
Calls: loadNamespace ... namespaceImportFrom -> asNamespace -> loadNamespace
Execution halted
[UPDATE] 
The reason this is uploaded late is because I just realized what the issue with the PDF formatting was. Apparently something is wrong with my code where /newpage does not work and completely breaks the knit. That's the only change between this version and my RMD that was uploaded last week, so I hope this doesn't count as late. If it does, please just grade what I had turned in at the time. Thank you!
