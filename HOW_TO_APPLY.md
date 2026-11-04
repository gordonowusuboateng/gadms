# Fix paper navigation links in the GADMs repository

The live repository stores the paper and bibliography files at the ROOT, not in papers/, resources/, references/.

1. Extract this ZIP.
2. Open https://github.com/gordonowusuboateng/generative-autonomous-driving-models
3. Click **Add file > Upload files**.
4. Upload all the extracted `.md` files from this folder to the repository root. **Do not upload the ZIP itself.**
5. Choose to replace existing files when prompted and commit.
6. Test the links under Research taxonomy and Full bibliography in README.

Fixes included:
- README links now use root file paths.
- Research collection bottom bibliography links now point to root bibliography.md.
- ParkDiffusion++ now links to its supplied 2026 arXiv preprint, rather than ParkDiffusion DOI.
- SceneDiffuser++ now links to its own 2025 CVPR DOI, rather than SceneDiffuser DOI.
- Some ECCV proceedings entries now use the Springer DOI already encoded in the supplied BibTeX keys.

These files retain the repository's current root-level structure. No need to create a website or move folders.
