CCEndlessScrollingTileMap
=========================

A tile map for large board games

Goals:  
* Maintain ~50-60 FPS

Todo:  
* Lazy loading of fresh tiles in large blocks (20-100 tiles) from server
* Slice up and lazy load in background image of static graphics (Like Google Maps)
* Do not render background image tiles that are off screen
* Parse colors from image into map data (like forest, water, mountains and other static

Done:  
* Do not render tiles that are off screen
* Combine Cocos2D with UIScrollView to get the native iOS feeling