#awesome-vcs

A curated list of awesome version control libraries. 

I like to keep everything under version control. This is a list of utilities that allow you to do that.

## DNS

 - [clouddns](https://github.com/jhawthorn/clouddns) (Cloudfront)
 - [namesync](https://github.com/dnerdy/namesync) (cloudflare)

## Configuration

- [etckeeper](https://github.com/joeyh/etckeeper)

## Passwords

- http://stackoverflow.com/questions/559611/password-storage-in-source-control
- John Resig's [blog post](http://ejohn.org/blog/keeping-passwords-in-source-control/)
- [pass](http://www.passwordstore.org/), standard unix password manager (encrypt, then commit)
- [ansible-vault](https://docs.ansible.com/playbooks_vault.html) encrypted storage for ansible

## Dotfiles

- <https://dotfiles.github.io/>
- [Arch Wiki Guide](https://wiki.archlinux.org/index.php/Dotfiles#Version_control)
- [gnu stow](http://www.gnu.org/software/stow/)

## Vim

- [http://www.terminally-incoherent.com/blog/2012/03/12/putting-your-vim-files-under-version-control/](putting-your-vim-files-under-version-control)

## Media

- [Git Large File Storage](https://git-lfs.github.com/)

## Encrypted Storage

- [HN Thread](https://news.ycombinator.com/item?id=8264496) for blackbox, with various alternatives suggested
- [git-crypt](https://www.agwa.name/projects/git-crypt/) - git-crypt enables transparent encryption and decryption of files in a git repository
- [Blog post](http://dsernst.com/2015/06/09/git-crypt-is-git--encryption/) on git-crypt
- [transcrypt](https://github.com/elasticdog/transcrypt) - transparently encrypt files within a git repository
- [blackbox](https://github.com/StackExchange/blackbox) - use decryption keys per user, meaning that there is no single shared password
- [git-encrypt](https://github.com/shadowhand/git-encrypt) - Slightly older technique

## Designers

- [pixelapse](https://www.pixelapse.com/) - Visual version control and collaboration workflow
- [Adobe Version Cue](http://sixrevisions.com/project-management/the-ultimate-guide-to-version-control-for-designers/) - Blog post explaining version control to designers

## Music

- [lilypond](http://www.lilypond.org/features.html) - version control for sheet music. Think Latex for sheet music
- [tunemachine](https://github.com/jez/tunemachine) - Version control for spotify playlists.
 
## Database

- Jeff Atwood's [blog post](http://blog.codinghorror.com/get-your-database-under-version-control/)
 
## Backups

- [bup](https://github.com/bup/bup) - Very efficient backup system based on the git packfile format, providing fast incremental saves and global deduplication (among and within files, including virtual machine images)
