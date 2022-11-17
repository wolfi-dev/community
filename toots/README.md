# The toots/ folder

To create a new toot create a new `*.toot` file in this `toots/` folder.

<kbd>[Create new toot](../../../new/main/?filename=toots/<your-path>.toot)</kbd>

## Example

Create a new file `toots/hello-world.toot` with the content

```
Hello, world!
```

You can use subfolders, e.g. `toots/2020-11/hello-world.toot`, as long as the file is in the `toots/` folder and has the `.toot` file extension

## Create a toot with a poll

A toot including a poll must end with 2-4 options in the following format

```
Here is some text

[ ] option A
[ ] option B
[ ] option C
[ ] option D
```

## Notes

- Only newly created files are handled, deletions, updates or renames are ignored.
- Toots posted from other Mastodon clients will not be imported as `*.toot` files.
- If you need to rename an existing toot file, please do so locally using [`git mv old_filename new_filename`](https://help.github.com/en/articles/renaming-a-file-using-the-command-line), otherwise it may occur as deleted and added which would trigger a new toot.
- Your message must fit into a single toot (typically 500 characters).

## Questions?

If you have any further questions or suggestions, please create an issue at https://github.com/joschi/toot-together/issues/new
