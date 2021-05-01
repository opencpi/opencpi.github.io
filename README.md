__THIS REPOSITORY IS OBSOLETE__
This project is hosted at [gitlab.com/opencpi](https://gitlab.com/opencpi/opencpi), since 2019.
Older branches and tags remain here for historical reasons.

Original repo layout:
 * `/` (pdfs)
 * `assets/` (pdfs)
 * `bsp_e310/` (pdfs)
 * `core/` (pdfs)
 * `ide/` IDE binary JAR storage
 * `repo/` YUM repo with top-level repo files

"Versioned" repo layout added:
 * `releases` per-subdir

Merging them, we now have the PDFs from the original layout all be symlinks to
`releases/latest/doc/` to not affect any legacy links.

In the future (1.6?) we will try to make the internal links "smarter" and use the
`releases/` subdir
