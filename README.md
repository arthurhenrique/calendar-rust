<p align="center">
  <img src="https://user-images.githubusercontent.com/3329711/116007073-5c9f4380-a5e4-11eb-9d79-aa0aab50c14d.png">
</p>

⚡️ Lightning-fast and minimal calendar command line. It's similar to `cal`.
Written in Rust 🦀

## How Can Install?

```sh
$ cargo install rusti-cal
```

## Usage

```sh
$ rusti-cal <year>
```

## Hands On

![hands-on](./doc/rusti-cal.gif)

## Optional Usage

+ Start Week With Sunday (Default)

```sh
$ rusti-cal <year> --starting-day 0
```

+ Start Week With Mondays

```sh
$ rusti-cal <year> --starting-day 1
```

+ Start Week With Tuesday

```sh
$ rusti-cal <year> --starting-day 2
```

+ Start Week With Wednesday

```sh
$ rusti-cal <year> --starting-day 3
```

+ Start Week With Thursday

```sh
$ rusti-cal <year> --starting-day 4
```

+ Start Week With Friday

```sh
$ rusti-cal <year> --starting-day 5
```

+ Start Week With Saturday

```sh
$ rusti-cal <year> --starting-day 6
```
