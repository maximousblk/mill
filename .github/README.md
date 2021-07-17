# mill

Set of GitHub Actions for me to build my favorite projects.

I had this set up in a private repo earlier but even though I rarely used it, long build times for some projects drained the 2000 minute quota very fast. So I decided to make this more presentable and make it public to ~~cheat~~ avoid the usage limit.

## Usage

You can [Use this template](https://github.com/maximousblk/mill/generate) to create a fresh setup.

1. Got to the Actions tab
2. Select the language of your project
3. Click on the `Run Workflow ▼` dropdown
4. Fill out the form and click `Run Workflow`

All the builds will be available as releases.

List supported Languages:

- [x] Rust
- [x] Go
- [x] Deno
- [ ] Node
- [ ] C
- [ ] C++
- [ ] Run Build Command

Some projects may not build properly if they require a special build process or environment.

## License

The contents of this repository are licensed under [The MIT License](./.github/LICENSE).
