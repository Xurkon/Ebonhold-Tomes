# Changelog

## [5.11.05-Ebonhold] - 2026-01-31

### Fixed
- **WishList Crash**: Fixed a Lua error in `Core/WishList.lua` where iterating over the wishlist table would crash if it contained non-table values (e.g., string keys like `Name = "Wishlists"`). Added type checking `if type(v) == "table"` to ensuring loops only process valid wishlist tables.

### Added
- **Ebonhold Integration**: Added Ebonhold Tomes to the World Events loot tables.
- **Project Structure**: Integrated full AtlasLoot suite into `Ebonhold-Tomes` repository.
