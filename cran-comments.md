## Test environments
- R-hub windows-x86_64-devel (r-devel)
- R-hub ubuntu-gcc-release (r-release)
- R-hub fedora-clang-devel (r-devel)

## R CMD check results
- On R-hub ubuntu-gcc-release (r-release) and fedora-clang-devel (r-devel)
  
  checking CRAN incoming feasibility ... NOTE
  Maintainer: Christopher Casement <casementc@gmail.com>
  
  This is a new package submission.

- On fedora-clang-devel (r-devel) only
  
  checking HTML version of manual ... NOTE
  Skipping checking HTML validation: no command 'tidy' found

  After looking online, I believe this is something I am unable to change.

0 errors v | 0 warnings v | 2 note x
