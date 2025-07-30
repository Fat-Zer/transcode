# About this repository

This repository preserves the codebase of transcode, a now-discontinued video
stream processing utility. It was combined solely for historical purpose, and
there are no plans for future development. However some patched accumulated
over time are also available in`patches/*` branches. If you wish to share a
patch feel free to send a PR.

For the information about the project itself, see the original README.


### Branches:

- `master` - based on the latest transcode-1.1.7 release and includes this
  description and a `.gitignore` file
- `old-dev/transcode_1_2` - contains the former master branch from the original
  repository, aimed at developing the next major release of Transcode, which
  were never released.
- `transcode_1_1` - an original branch with bug fixes for transcode-1.1.x.
  Unfortunately, some recent history was lost, so the tip was amended with code
  from the latest release tarball.
- `transcode_1_0` - an original branch with bug fixes for transcode-1.0.x.
- `old-dev/release-0_6_13-patches` and `old-dev/new-module-system` - other branches
  from the original repository.
- `patches/gentoo` - the branch includes patches used to build transcode
  on Gentoo before the package got removed. The commit messages contain some
  additional information like original patch names, where the patch origins
  from as well as authorship information to the best it could be recovered.
- `patches/gentoo-trinity` - set of patches used by [TDE gentoo overlay][5].
  Technically thees patches actually originate from this repository.

### Links

* [Archived version][1] of the original project page (last updated in 2004)  
* [Archived version][2] of the second site for the original project (last updated in 2009)  
* [Ubuntu's Launchpad][3], which still contains the original tarball for version 1.1.7
* PLD Linux [transcode maintance repository][6]

### Acknowledgements

Thanks to all developers, who worked and contributed to transcode over time.

Special thanks to Andrew Church for providing the [Mercurial bundle][4], which was used to seed this repository.


[1]: https://web.archive.org/web/20041209014202/http://www.theorie.physik.uni-goettingen.de/~ostreich/transcode/
[2]: https://web.archive.org/web/20110424210638/http://www.transcoding.org/cgi-bin/transcode
[3]: https://launchpad.net/ubuntu/+source/transcode/3:1.1.7-8
[4]: https://achurch.org/transcode-hg.bundle
[5]: https://mirror.git.trinitydesktop.org/gitea/TDE/tde-packaging-gentoo
[6]: https://git.pld-linux.org/?p=packages/transcode.git
