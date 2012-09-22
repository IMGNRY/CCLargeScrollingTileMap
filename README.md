CCEndlessScrollingTileMap
=========================

A tile map for large board games

Goals:  
* Maintain ~60 FPS (Do not render tiles that are off screen)
* Combine Cocos2D with UIScrollView to get the native iOS feeling
* Lazy loading of fresh tiles in large blocks from server
* Parse colors from image into map data