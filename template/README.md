# Rust Template

A simple template/example repo for the set-up of Rust projects including a gitignore and a dockerfile.

## Set-up

You normally create a Rust project with the following command.

```
cargo new project_name
```

## Build

```
cargo build
```


## Run the test cases
```
cargo test
```
In Rust you write the unit tests directly in the implementation files. 
Only integration tests are moved into an own module/crate.
The template also includes an example.

## Run 

```
cargo run
```


## Docker

```
docker build -t rust-template .
```

```
docker run rust-template
```
