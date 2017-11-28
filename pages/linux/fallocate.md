# fallocate

> Allocate hard drive space for a file. Useful for
> creating large files for testing.

- Allocate 82 bytes to a file:

`fallocate -l 82 {{filename}}`

- Allocate 5GiB to a file:

`fallocate -l 5G {{filename}}`

