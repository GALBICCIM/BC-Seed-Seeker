# The Battle Cats : Seed Seeker

This program is a code that corrects errors in the [original author's code](https://github.com/fieryhenry/BattleCatsGachaSeeker).

## Code Issues and Fixes

-  Fixed **repeated type assignment**
-  Fixed an issue in the `get_gatya_slot_data` function of the `gatya_data.rs` code where the **cat_id** variable was inserted into a vector with the same index
-  Added debugging code

## How to run

```bash
git clone <url>
cd BC-Seed-Seeker
cargo run --release
```
