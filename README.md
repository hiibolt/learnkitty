# `learnkitty`

## WIP

## building typescript client
- `cargo test` from root - builds typescript types with `ts_rs`, then builds typescript client via `learnkitty-backend` test
- gets put in `learnkitty-api/learnkitty-typescript-api`
- either copy the output to `learnkitty-frontend/src/types/learnkitty-typescript-api` **or ideally add a symbolic link** `ln -s "$HOME/Development/learnkitty/learnkitty-api/learnkitty-typescript-api" "$HOME/Development/learnkitty/learnkitty-frontend/src/types"`. 
    - symlinks still work fine with gh :3