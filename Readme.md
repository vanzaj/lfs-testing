# Testing Large File Storage

Repo size after adding the image: 245 Kb. After 1 image modification: 324 Kb,
after another modificaton: 400 Kb. After `git lfs prune`, the size is 296Kb.
I.e. the image is *not* stored in regular git blobs.
