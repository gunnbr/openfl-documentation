# Feature Matrix

## openfl.display

### Bitmap

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bitmapData | yes | yes | yes | yes |
| pixelSnapping | yes | ignored | ignored | ignored |
| smoothing | yes | yes | yes | yes |

### BitmapData

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| height | yes | yes | yes | yes |
| rect | yes | yes | yes | yes |
| transparent | yes | yes | yes | yes |
| width | yes | yes | yes | yes |
| applyFilter | yes | partial | partial | planned |
| clone | yes | yes | yes | yes |
| colorTransform | yes | yes | yes | yes |
| copyChannel | yes | yes | yes | yes |
| copyPixels | yes | yes | yes | yes |
| dispose | yes | yes | yes | yes |
| draw | yes | yes | yes* | planned |
| encode | yes | planned | yes | planned |
| fillRect | yes | yes | yes | yes |
| floodFill | yes | yes | yes | yes |
| generateFilterRect | yes | ignored | ignored | ignored |
| getColorBoundsRect | yes | ignored | ignored | ignored |
| getPixel | yes | yes | yes | yes |
| getPixel32 | yes | yes | yes | yes |
| getPixels | yes | yes | yes | yes |
| getVector | yes | yes | yes | yes |
| histogram | yes | yes | yes | yes |
| hitTest | yes | planned | no | planned |
| lock | yes | yes | yes | yes |
| noise | yes | planned | yes | planned |
| paletteMap | yes | yes | yes | yes |
| perlinNoise | yes | no | partial | no |
| scroll | yes | planned | yes | planned |
| setPixel | yes | yes | yes | yes |
| setPixel32 | yes | yes | yes | yes |
| setPixels | yes | yes | yes | yes |
| setVector | yes | yes | yes | yes |
| threshold | yes | yes | yes | yes |
| unlock | yes | yes | yes | yes |

### DisplayObject

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| alpha | yes | yes | yes | yes |
| blendMode | yes | ignored | yes* | partial |
| cacheAsBitmap | yes | yes | yes* | planned |
| filters | yes | yes | yes | yes |
| loaderInfo | yes | yes | yes | yes |
| mouseX | yes | yes | yes | yes |
| mouseY | yes | yes | yes | yes |
| name | yes | yes | yes | yes |
| opaqueBackground | yes | planned | yes | planned |
| parent | yes | yes | yes | yes |
| root | yes | planned | partial | planned |
| rotation | yes | yes | yes | yes |
| scale9Grid | yes | ignored | ignored | ignored |
| scaleX | yes | yes | yes | yes |
| scaleY | yes | yes | yes | yes |
| scrollRect | yes | yes | yes | yes |
| stage | yes | yes | yes | yes |
| transform | yes | yes | yes | yes |
| visible | yes | yes | yes | yes |
| width | yes | yes | yes | yes |
| x | yes | yes | yes | yes |
| y | yes | yes | yes | yes |

### DisplayObjectContainer

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| mouseChildren | yes | yes | yes | yes |
| numChildren | yes | yes | yes | yes |
| tabChildren | yes | ignored | ignored | ignored |
| addChild | yes | yes | yes | yes |
| addChildAt | yes | yes | yes | yes |
| areInaccessibleObjectsUnderPoint | yes | ignored | ignored | ignored |
| contains | yes | yes | yes | yes |
| getChildAt | yes | yes | yes | yes |
| getChildByName | yes | yes | yes | yes |
| getChildIndex | yes | yes | yes | yes |
| getObjectsUnderPoint | yes | yes | yes | yes |
| removeChild | yes | yes | yes | yes |
| removeChildAt | yes | yes | yes | yes |
| removeChildren | yes | yes | yes | yes |
| setChildIndex | yes | yes | yes | yes |
| swapChildren | yes | yes | yes | yes |
| swapChildrenAt | yes | yes | yes | yes |

### FrameLabel

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| frame | yes | yes | yes | yes |
| name | yes | yes | yes | yes |

### Graphics

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| beginBitmapFill | yes | yes | yes | yes |
| beginFill | yes | yes | yes | yes |
| beginGradientFill | yes | no | partial | no |
| clear | yes | yes | yes | yes |
| copyFrom | yes | yes | no | yes |
| cubicCurveTo | yes | yes | no | yes |
| curveTo | yes | yes | yes | yes |
| drawCircle | yes | yes | yes | yes |
| drawEllipse | yes | yes | yes | yes |
| drawGraphicsData | yes | no | yes | no |
| drawPath | yes | no | yes | no |
| drawRect | yes | yes | yes | yes |
| drawRoundRect | yes | yes | yes | yes |
| drawRoundRectComplex | yes | no | no | no |
| drawTiles | yes | yes | yes | yes |
| drawTriangles | yes | yes | yes | yes |
| endFill | yes | yes | yes | yes |
| lineBitmapStyle | yes | no | partial | no |
| lineGradientStyle | yes | no | partial | no |
| lineStyle | yes | partial | partial | partial |
| lineTo | yes | yes | yes | yes |
| moveTo | yes | yes | yes | yes |

### GraphicsBitmapFill

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bitmapData | yes | yes | yes | yes |
| matrix | yes | yes | yes | yes |
| repeat | yes | yes | yes | yes |
| smooth | yes | yes | yes | yes |

### GraphicsEndFill

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### GraphicsGradientFill

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| alphas | yes | yes | yes | yes |
| colors | yes | yes | yes | yes |
| focalPointRatio | yes | yes | yes | yes |
| interpolationMethod | yes | yes | yes | yes |
| matrix | yes | yes | yes | yes |
| ratios | yes | yes | yes | yes |
| spreadMethod | yes | yes | yes | yes |
| type | yes | yes | yes | yes |

### GraphicsPath

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| commands | yes | yes | yes | yes |
| data | yes | yes | yes | yes |
| winding | yes | yes | yes | yes |
| curveTo | yes | yes | yes | yes |
| lineTo | yes | yes | yes | yes |
| moveTo | yes | yes | yes | yes |
| wideLineTo | yes | yes | yes | yes |
| wideMoveTo | yes | yes | yes | yes |

### GraphicsSolidFill

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| alpha | yes | yes | yes | yes |
| color | yes | yes | yes | yes |

### GraphicsStroke

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| caps | yes | yes | yes | yes |
| fill | yes | yes | yes | yes |
| joints | yes | yes | yes | yes |
| miterLimit | yes | yes | yes | yes |
| pixelHinting | yes | yes | yes | yes |
| scaleMode | yes | yes | yes | yes |
| thickness | yes | yes | yes | yes |

### InteractiveObject

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| doubleClickEnabled | yes | ignored | ignored | ignored |
| focusRect | yes | ignored | ignored | ignored |
| mouseEnabled | yes | yes | yes | yes |
| needsSoftKeyboard | yes | ignored | partial | ignored |
| softKeyboardInputAreaOfInterest | yes | ignored | ignored | ignored |
| tabEnabled | yes | ignored | ignored | ignored |
| tabIndex | yes | ignored | ignored | ignored |

### Loader

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| content | yes | yes | yes | yes |
| contentLoaderInfo | yes | yes | yes | yes |
| close | yes | no | no | no |
| load | yes | yes | yes | yes |
| loadBytes | yes | yes | yes | yes |
| unload | yes | yes | yes | yes |
| unloadAndStop | yes | no | no | no |

### LoaderInfo

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| applicationDomain | yes | ignored | ignored | ignored |
| bytes | yes | yes | yes | yes |
| bytesLoaded | yes | yes | yes | yes |
| bytesTotal | yes | yes | yes | yes |
| childAllowsParent | yes | ignored | ignored | ignored |
| content | yes | yes | yes | yes |
| contentType | yes | partial | partial | partial |
| frameRate | yes | ignored | ignored | ignored |
| height | yes | yes | yes | yes |
| loader | yes | yes | yes | yes |
| parameters | yes | ignored | ignored | ignored |
| parentAllowsChild | yes | ignored | ignored | ignored |
| sameDomain | yes | ignored | ignored | ignored |
| sharedEvents | yes | ignored | ignored | ignored |
| uncaughtErrorEvents | yes | partial | partial | partial |
| url | yes | yes | yes | yes |
| width | yes | yes | yes | yes |

### MovieClip

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| currentFrame | yes | yes | yes | yes |
| currentFrameLabel | yes | yes | yes | yes |
| currentLabel | yes | yes | yes | yes |
| currentLabels | yes | yes | yes | yes |
| enabled | yes | yes | yes | yes |
| framesLoaded | yes | yes | yes | yes |
| totalFrames | yes | yes | yes | yes |
| gotoAndPlay | yes | yes | yes | yes |
| gotoAndStop | yes | yes | yes | yes |
| nextFrame | yes | yes | yes | yes |
| play | yes | yes | yes | yes |
| prevFrame | yes | yes | yes | yes |
| stop | yes | yes | yes | yes |

### OpenGLView

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| isSupported | yes | yes | yes | yes |
| render | ignored | yes | yes | yes |

### Shape

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| graphics | yes | yes | yes | yes |

### SimpleButton

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| downState | yes | yes | yes | yes |
| enabled | yes | yes | yes | yes |
| hitTestState | yes | yes | yes | yes |
| overState | yes | yes | yes | yes |
| soundTransform | yes | ignored | ignored | ignored |
| trackAsMenu | yes | ignored | ignored | ignored |
| upState | yes | yes | yes | yes |
| useHandCursor | yes | yes | ignored | ignored |

### Sprite

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| buttonMode | yes | yes | ignored | ignored |
| graphics | yes | yes | yes | yes |
| useHandCursor | yes | yes | ignored | ignored |
| startDrag | yes | yes | yes | yes |
| stopDrag | yes | yes | yes | yes |

### Stage

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| align | yes | no | partial | no |
| color | yes | yes | yes | yes |
| displayState | yes | partial | yes | yes |
| focus | yes | partial | partial | partial |
| frameRate | yes | ignored | yes | yes |
| quality | yes | ignored | partial | ignored |
| stageFocusRect | yes | ignored | ignored | ignored |
| scaleMode | yes | no | partial | no |
| stageHeight | yes | yes | yes | yes |
| stageWidth | yes | yes | yes | yes |
| invalidate | yes | yes | yes | yes |

### Tilesheet

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| addTileRect | yes | yes | yes | yes |
| drawTiles | yes | yes | yes | yes |

## openfl.errors

### ArgumentError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### EOFError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### Error

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| errorID | yes | yes | yes | yes |
| message | yes | yes | yes | yes |
| name | yes | yes | yes | yes |
| getStackTrace | yes | yes | yes | yes |

### IllegalOperationError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### IOError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### RangeError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### SecurityError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### TypeError

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

## openfl.events

### AccelerometerEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| accelerationX | yes | yes | yes | yes |
| accelerationY | yes | yes | yes | yes |
| accelerationZ | yes | yes | yes | yes |
| timestamp | yes | yes | yes | yes |

### AsyncErrorEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| error | yes | yes | yes | yes |

### ContextMenuEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| contextMenuOwner | yes | ignored | ignored | ignored |
| mouseTarget | yes | ignored | ignored | ignored |

### DataEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| data | yes | yes | yes | yes |

### ErrorEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| errorID | yes | yes | yes | yes |

### Event

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bubbles | yes | yes | yes | yes |
| cancelable | yes | yes | yes | yes |
| currentTarget | yes | yes | yes | yes |
| eventPhase | yes | yes | yes | yes |
| target | yes | yes | yes | yes |
| type | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |
| isDefaultPrevented | yes | yes | yes | yes |
| stopImmediatePropagation | yes | yes | yes | yes |
| stopPropagation | yes | yes | yes | yes |

### EventDispatcher

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| addEventListener | yes | yes | yes | yes |
| dispatchEvent | yes | yes | yes | yes |
| hasEventListener | yes | yes | yes | yes |
| removeEventListener | yes | yes | yes | yes |
| willTrigger | yes | yes | yes | yes |

### FocusEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| keyCode | yes | yes | yes | yes |
| relatedObject | yes | yes | yes | yes |
| shiftKey | yes | yes | yes | yes |

### HTTPStatusEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| responseHeaders | yes | yes | yes | yes |
| responseURL | yes | yes | yes | yes |
| status | yes | yes | yes | yes |

### IOErrorEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### JoystickEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| axis | no | planned | yes | planned |
| device | no | planned | yes | planned |
| id | no | planned | yes | planned |
| x | no | planned | yes | planned |
| y | no | planned | yes | planned |
| z | no | planned | yes | planned |

### KeyboardEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| altKey | yes | yes | yes | yes |
| charCode | yes | yes | yes | yes |
| ctrlKey | yes | yes | yes | yes |
| commandKey | yes | yes | yes | yes |
| controlKey | yes | yes | yes | yes |
| keyCode | yes | yes | yes | yes |
| keyLocation | yes | yes | yes | yes |
| shiftKey | yes | yes | yes | yes |

### MouseEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| altKey | yes | yes | yes | yes |
| buttonDown | yes | yes | yes | yes |
| commandKey | yes | yes | yes | yes |
| clickCount | yes | yes | yes | yes |
| ctrlKey | yes | yes | yes | yes |
| delta | yes | yes | yes | yes |
| localX | yes | yes | yes | yes |
| localY | yes | yes | yes | yes |
| relatedObject | yes | yes | yes | yes |
| shiftKey | yes | yes | yes | yes |
| stageX | yes | yes | yes | yes |
| stageY | yes | yes | yes | yes |

### NetStatusEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| info | yes | yes | yes | yes |

### ProgressEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bytesLoaded | yes | yes | yes | yes |
| bytesTotal | yes | yes | yes | yes |

### SampleDataEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| data | yes | planned | yes | planned |
| position | yes | planned | yes | planned |

### SecurityErrorEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### TextEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| text | yes | yes | yes | planned |

### TimerEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

### TouchEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| altKey | yes | yes | yes | yes |
| buttonDown | yes | yes | yes | yes |
| commandKey | yes | yes | yes | yes |
| ctrlKey | yes | yes | yes | yes |
| delta | yes | yes | yes | yes |
| isPrimaryTouchPoint | yes | yes | yes | yes |
| localX | yes | yes | yes | yes |
| localY | yes | yes | yes | yes |
| pressure | yes | ignored | ignored | ignored |
| relatedObject | yes | yes | yes | yes |
| shiftKey | yes | yes | yes | yes |
| sizeX | yes | ignored | ignored | ignored |
| sizeY | yes | ignored | ignored | ignored |
| stageX | yes | yes | yes | yes |
| stageY | yes | yes | yes | yes |
| touchPointID | yes | yes | yes | yes |

### UncaughtErrorEvent

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| error | yes | yes | yes | yes |

### UncaughtErrorEvents

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| (available) | yes | yes | yes | yes |

## openfl.external

### ExternalInterface

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| available | yes | yes | ignored | ignored |
| marshallExceptions | yes | ignored | ignored | ignored |
| objectID | yes | ignored | ignored | ignored |

## openfl.filters

### BitmapFilter

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| clone | yes | yes | yes | yes |

### BlurFilter

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| blurX | yes | ignored | yes | ignored |
| blurY | yes | ignored | yes | ignored |
| quality | yes | ignored | yes | ignored |

### ColorMatrixFilter

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| matrix | yes | yes | yes | planned |

### DropShadowFilter

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| alpha | yes | ignored | yes | ignored |
| angle | yes | ignored | yes | ignored |
| blurX | yes | ignored | yes | ignored |
| blurY | yes | ignored | yes | ignored |
| color | yes | ignored | yes | ignored |
| distance | yes | ignored | yes | ignored |
| hideObject | yes | ignored | yes | ignored |
| inner | yes | ignored | yes | ignored |
| knockout | yes | ignored | yes | ignored |
| quality | yes | ignored | yes | ignored |
| strength | yes | ignored | yes | ignored |

### GlowFilter

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| alpha | yes | ignored | yes | ignored |
| blurX | yes | ignored | yes | ignored |
| blurY | yes | ignored | yes | ignored |
| color | yes | ignored | yes | ignored |
| inner | yes | ignored | yes | ignored |
| knockout | yes | ignored | yes | ignored |
| quality | yes | ignored | yes | ignored |
| strength | yes | ignored | yes | ignored |

## openfl.geom

### ColorTransform

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| alphaMultiplier | yes | yes | yes | yes |
| alphaOffset | yes | yes | yes | yes |
| blueMultiplier | yes | yes | yes | yes |
| blueOffset | yes | yes | yes | yes |
| color | yes | yes | yes | yes |
| greenMultiplier | yes | yes | yes | yes |
| greenOffset | yes | yes | yes | yes |
| redMultiplier | yes | yes | yes | yes |
| redOffset | yes | yes | yes | yes |
| concat | yes | yes | yes | yes |

### Matrix

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| a | yes | yes | yes | yes |
| b | yes | yes | yes | yes |
| c | yes | yes | yes | yes |
| d | yes | yes | yes | yes |
| tx | yes | yes | yes | yes |
| ty | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |
| concat | yes | yes | yes | yes |
| copyColumnFrom | yes | yes | yes | yes |
| copyColumnTo | yes | yes | yes | yes |
| copyFrom | yes | yes | yes | yes |
| copyRowFrom | yes | yes | yes | yes |
| copyRowTo | yes | yes | yes | yes |
| createBox | yes | yes | yes | yes |
| createGradientBox | yes | yes | yes | yes |
| equals | yes | yes | yes | yes |
| deltaTransformPoint | yes | yes | yes | yes |
| identity | yes | yes | yes | yes |
| invert | yes | yes | yes | yes |
| mult | yes | yes | yes | yes |
| rotate | yes | yes | yes | yes |
| scale | yes | yes | yes | yes |
| setRotation | yes | yes | yes | yes |
| setTo | yes | yes | yes | yes |
| transformPoint | yes | yes | yes | yes |
| translate | yes | yes | yes | yes |

### Matrix3D

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| determinant | yes | yes | yes | yes |
| position | yes | yes | yes | yes |
| rawData | yes | yes | yes | yes |
| append | yes | yes | yes | yes |
| appendRotation | yes | yes | yes | yes |
| appendScale | yes | yes | yes | yes |
| appendTranslation | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |
| copyColumnFrom | yes | yes | yes | yes |
| copyColumnTo | yes | yes | yes | yes |
| copyFrom | yes | yes | yes | yes |
| copyRawDataFrom | yes | yes | yes | yes |
| copyRawDataTo | yes | yes | yes | yes |
| copyRowFrom | yes | yes | yes | yes |
| create2D | no | yes | yes | yes |
| createABCD | no | yes | yes | yes |
| createOrtho | no | yes | yes | yes |
| copyRowTo | yes | yes | yes | yes |
| copyToMatrix3D | yes | yes | yes | yes |
| decompose | yes | yes | yes | yes |
| deltaTransformVector | yes | yes | yes | yes |
| getAxisRotation | yes | yes | yes | yes |
| identity | yes | yes | yes | yes |
| interpolate | yes | yes | yes | yes |
| interpolateTo | yes | yes | yes | yes |
| invert | yes | yes | yes | yes |
| pointAt | yes | yes | yes | yes |
| prepend | yes | yes | yes | yes |
| prependRotation | yes | yes | yes | yes |
| prependScale | yes | yes | yes | yes |
| prependTranslation | yes | yes | yes | yes |
| recompose | yes | yes | yes | yes |
| transformVector | yes | yes | yes | yes |
| transformVectors | yes | yes | yes | yes |
| transpose | yes | yes | yes | yes |

### PerspectiveProjection

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| fieldOfView | yes | yes | yes | yes |
| focalLength | yes | yes | yes | yes |
| projectionCenter | yes | yes | yes | yes |
| toMatrix3D | yes | yes | yes | yes |

### Point

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| length | yes | yes | yes | yes |
| x | yes | yes | yes | yes |
| y | yes | yes | yes | yes |
| add | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |
| distance | yes | yes | yes | yes |
| equals | yes | yes | yes | yes |
| interpolate | yes | yes | yes | yes |
| normalize | yes | yes | yes | yes |
| offset | yes | yes | yes | yes |
| polar | yes | yes | yes | yes |
| setTo | yes | yes | yes | yes |
| subtract | yes | yes | yes | yes |

### Rectangle

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bottom | yes | yes | yes | yes |
| bottomRight | yes | yes | yes | yes |
| height | yes | yes | yes | yes |
| left | yes | yes | yes | yes |
| right | yes | yes | yes | yes |
| size | yes | yes | yes | yes |
| top | yes | yes | yes | yes |
| topLeft | yes | yes | yes | yes |
| width | yes | yes | yes | yes |
| x | yes | yes | yes | yes |
| y | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |
| contains | yes | yes | yes | yes |
| containsPoint | yes | yes | yes | yes |
| containsRect | yes | yes | yes | yes |
| copyFrom | yes | yes | yes | yes |
| equals | yes | yes | yes | yes |
| inflate | yes | yes | yes | yes |
| inflatePoint | yes | yes | yes | yes |
| intersection | yes | yes | yes | yes |
| intersects | yes | yes | yes | yes |
| isEmpty | yes | yes | yes | yes |
| offset | yes | yes | yes | yes |
| offsetPoint | yes | yes | yes | yes |
| setEmpty | yes | yes | yes | yes |
| setTo | yes | yes | yes | yes |
| transform | yes | yes | yes | yes |
| union | yes | yes | yes | yes |

### Transform

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| colorTransform | yes | yes | yes | yes |
| concatenatedColorTransform | yes | yes | yes | yes |
| concatenatedMatrix | yes | yes | yes | yes |
| matrix | yes | yes | yes | yes |
| pixelBounds | yes | ignored | ignored | ignored |

### Utils3D

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| projectVector | yes | yes | yes | yes |

### Vector3D

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| length | yes | yes | yes | yes |
| lengthSquared | yes | yes | yes | yes |
| w | yes | yes | yes | yes |
| x | yes | yes | yes | yes |
| y | yes | yes | yes | yes |
| z | yes | yes | yes | yes |
| add | yes | yes | yes | yes |
| angleBetween | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |
| copyFrom | yes | yes | yes | yes |
| crossProduct | yes | yes | yes | yes |
| decrementBy | yes | yes | yes | yes |
| distance | yes | yes | yes | yes |
| dotProduct | yes | yes | yes | yes |
| equals | yes | yes | yes | yes |
| incrementBy | yes | yes | yes | yes |
| nearEquals | yes | yes | yes | yes |
| negate | yes | yes | yes | yes |
| normalize | yes | yes | yes | yes |
| project | yes | yes | yes | yes |
| scaleBy | yes | yes | yes | yes |
| setTo | yes | yes | yes | yes |
| subtract | yes | yes | yes | yes |

## openfl.media

### ID3Info

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| album | yes | ignored | ignored | ignored |
| artist | yes | ignored | ignored | ignored |
| comment | yes | ignored | ignored | ignored |
| genre | yes | ignored | ignored | ignored |
| songName | yes | ignored | ignored | ignored |
| track | yes | ignored | ignored | ignored |
| year | yes | ignored | ignored | ignored |

### Sound

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bytesLoaded | yes | yes | yes | yes |
| bytesTotal | yes | yes | yes | yes |
| id3 | yes | ignored | ignored | ignored |
| isBuffering | yes | ignored | ignored | ignored |
| length | yes | yes | yes | yes |
| url | yes | yes | yes | yes |
| close | yes | yes | yes | yes |
| load | yes | yes | partial | partial |
| loadCompressedDataFromByteArray | yes | no | yes | partial |
| loadPCMFromByteArray | yes | no | yes | partial |
| play | yes | yes | yes | partial |

### SoundChannel

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| leftPeak | yes | ignored | ignored | ignored |
| position | yes | yes | yes | yes |
| rightPeak | yes | ignored | ignored | ignored |
| soundTransform | yes | yes | yes | yes |
| stop | yes | yes | yes | yes |

### SoundLoaderContext

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bufferTime | yes | ignored | ignored | ignored |
| checkPolicyFile | yes | ignored | ignored | ignored |

### SoundTransform

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| leftToLeft | yes | yes | yes | yes |
| leftToRight | yes | yes | yes | yes |
| pan | yes | yes | yes | yes |
| rightToLeft | yes | yes | yes | yes |
| rightToRight | yes | yes | yes | yes |
| volume | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |

### Video

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| deblocking | yes | ignored | ignored | ignored |
| smoothing | yes | ignored | ignored | ignored |
| attachNetStream | yes | yes | no | no |
| clear | yes | ignored | ignored | ignored |

## openfl.net

### NetConnection

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| connect | yes | yes | ignored | ignored |

### NetStream

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| audioCodec | yes | ignored | ignored | ignored |
| bufferLength | yes | ignored | ignored | ignored |
| bufferTime | yes | ignored | ignored | ignored |
| bytesLoaded | yes | ignored | ignored | ignored |
| client | yes | ignored | ignored | ignored |
| currentFPS | yes | ignored | ignored | ignored |
| decodedFrames | yes | ignored | ignored | ignored |
| liveDelay | yes | ignored | ignored | ignored |
| objectEncoding | yes | ignored | ignored | ignored |
| soundTransform | yes | ignored | ignored | ignored |
| speed | yes | ignored | ignored | ignored |
| time | yes | ignored | ignored | ignored |
| videoCodec | yes | ignored | ignored | ignored |
| pause | yes | yes | ignored | ignored |
| play | yes | yes | ignored | ignored |
| resume | yes | yes | ignored | ignored |
| seek | yes | yes | ignored | ignored |
| togglePause | yes | yes | ignored | ignored |

### SharedObject

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| data | yes | yes | yes | yes |
| size | yes | yes | yes | yes |
| clear | yes | yes | yes | yes |
| flush | yes | yes | yes | yes |
| getLocal | yes | yes | yes | yes |
| setProperty | yes | yes | yes | yes |

### Socket

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bytesAvailable | yes | yes | yes | yes |
| bytesPending | yes | yes | yes | yes |
| timeout | yes | yes | yes | yes |
| objectEncoding | yes | ignored | ignored | ignored |
| endian | yes | yes | yes | yes |
| connected | yes | yes | yes | yes |
| connect | yes | yes | yes | yes |
| close | yes | yes | yes | yes |
| flush | yes | yes | yes | yes |
| readBoolean | yes | yes | yes | yes |
| readByte | yes | yes | yes | yes |
| readBytes | yes | yes | yes | yes |
| readDouble | yes | yes | yes | yes |
| readFloat | yes | yes | yes | yes |
| readInt | yes | yes | yes | yes |
| readMultiByte | yes | yes | yes | yes |
| readShort | yes | yes | yes | yes |
| readUnsignedByte | yes | yes | yes | yes |
| readUnsignedInt | yes | yes | yes | yes |
| readUnsignedShort | yes | yes | yes | yes |
| readUTF | yes | yes | yes | yes |
| readUTFBytes | yes | yes | yes | yes |
| writeBoolean | yes | yes | yes | yes |
| writeByte | yes | yes | yes | yes |
| writeBytes | yes | yes | yes | yes |
| writeDouble | yes | yes | yes | yes |
| writeFloat | yes | yes | yes | yes |
| writeInt | yes | yes | yes | yes |
| writeMultiByte | yes | yes | yes | yes |
| writeShort | yes | yes | yes | yes |
| writeUTF | yes | yes | yes | yes |
| writeUTFBytes | yes | yes | yes | yes |
| writeUnsignedInt | yes | yes | yes | yes |

### URLLoader

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bytesLoaded | yes | yes | yes | planned |
| bytesTotal | yes | yes | yes | planned |
| data | yes | yes | yes | planned |
| dataFormat | yes | yes | yes | planned |
| close | yes | ignored | ignored | ignored |
| load | yes | yes | yes | planned |

### URLRequest

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| contentType | yes | yes | yes | planned |
| data | yes | yes | yes | planned |
| method | yes | yes | yes | planned |
| requestHeaders | yes | yes | yes | planned |
| url | yes | yes | yes | planned |
| userAgent | yes | no | partial | planned |
| formatRequestHeaders | yes | yes | yes | planned |

### URLRequestHeader

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| name | yes | yes | yes | yes |
| value | yes | yes | yes | yes |

### URLVariables

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| decode | yes | yes | yes | yes |

### XMLSocket

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| connected | yes | yes | yes | ignored |
| timeout | yes | ignored | ignored | ignored |
| close | yes | yes | yes | ignored |
| connect | yes | yes | yes | ignored |
| connectWithProto | yes | partial | no | ignored |
| send | yes | yes | yes | ignored |

## openfl.sensors

### Accelerometer

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| isSupported | yes | ignored | yes | ignored |
| muted | yes | ignored | yes | ignored |
| setRequestedUpdateInterval | yes | ignored | yes | ignored |

## openfl.system

### ApplicationDomain

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| currentDomain | yes | ignored | ignored | ignored |
| parentDomain | yes | ignored | ignored | ignored |
| getDefinition | yes | ignored | ignored | ignored |
| hasDefinition | yes | ignored | ignored | ignored |

### Capabilities

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| hasAccessibility | yes | ignored | ignored | ignored |
| pixelAspectRatio | yes | yes | yes | planned |
| screenDPI | yes | yes | yes | planned |
| screenResolutionX | yes | yes | yes | planned |
| screenResolutionY | yes | yes | yes | planned |
| language | yes | yes | yes | planned |

### LoaderContext

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| allowCodeImport | yes | ignored | ignored | ignored |
| allowLoadBytesCodeExecution | yes | ignored | ignored | ignored |
| applicationDomain | yes | ignored | ignored | ignored |
| checkPolicyFile | yes | ignored | ignored | ignored |
| securityDomain | yes | ignored | ignored | ignored |

### Security

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| disableAVM1Loading | yes | ignored | ignored | ignored |
| exactSettings | yes | ignored | ignored | ignored |
| sandboxType | yes | ignored | ignored | ignored |
| allowDomain | yes | ignored | ignored | ignored |
| allowInsecureDomain | yes | ignored | ignored | ignored |
| loadPolicyFile | yes | ignored | ignored | ignored |

### SecurityDomain

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| currentDomain | yes | ignored | ignored | ignored |

### System

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| totalMemory | yes | ignored | yes | planned |
| useCodePage | yes | ignored | ignored | ignored |
| vmVersion | yes | ignored | ignored | ignored |
| exit | no | no | yes | planned |
| gc | no | no | yes | no |
| pause | no | no | yes | planned |
| resume | no | no | yes | planned |
| setClipboard | yes | no | no | planned |

## openfl.text

### Font

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| fontName | yes | yes | yes | yes |
| fontStyle | yes | ignored | ignored | ignored |
| fontType | yes | ignored | ignored | ignored |
| enumerateFonts | yes | partial | yes | partial |
| registerFont | yes | ignored | yes | yes |

### TextField

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| antiAliasType | yes | ignored | ignored | ignored |
| autoSize | yes | partial | partial | planned |
| background | yes | yes | yes | planned |
| backgroundColor | yes | yes | yes | planned |
| border | yes | yes | yes | planned |
| borderColor | yes | yes | yes | planned |
| bottomScrollV | yes | ignored | ignored | ignored |
| caretIndex | yes | ignored | ignored | ignored |
| caretPos | yes | ignored | ignored | ignored |
| defaultTextFormat | yes | yes | yes | planned |
| displayAsPassword | yes | no | yes | planned |
| embedFonts | yes | ignored | ignored | ignored |
| gridFitType | yes | ignored | ignored | ignored |
| htmlText | yes | partial | partial | planned |
| length | yes | yes | yes | planned |
| maxChars | yes | ignored | ignored | ignored |
| maxScrollH | yes | ignored | ignored | ignored |
| maxScrollV | yes | ignored | ignored | ignored |
| multiline | yes | yes | yes | planned |
| numLines | yes | yes | yes | planned |
| restrict | yes | ignored | ignored | ignored |
| scrollH | yes | ignored | ignored | ignored |
| scrollV | yes | ignored | ignored | ignored |
| selectable | yes | yes | yes | planned |
| selectionBeginIndex | yes | ignored | ignored | ignored |
| selectionEndIndex | yes | ignored | ignored | ignored |
| sharpness | yes | ignored | ignored | ignored |
| text | yes | yes | yes | planned |
| textColor | yes | yes | yes | planned |
| textHeight | yes | yes | yes | planned |
| textWidth | yes | yes | yes | planned |
| type | yes | yes | yes | planned |
| wordWrap | yes | yes | yes | planned |
| appendText | yes | yes | yes | planned |
| getCharBoundaries | yes | ignored | ignored | ignored |
| getCharIndexAtPoint | yes | ignored | ignored | ignored |
| getLineIndexAtPoint | yes | ignored | ignored | ignored |
| getLineMetrics | yes | ignored | ignored | ignored |
| getLineOffset | yes | ignored | ignored | ignored |
| getLineText | yes | ignored | ignored | ignored |
| getTextFormat | yes | yes | yes | planned |
| setSelection | yes | ignored | ignored | ignored |
| setTextFormat | yes | yes | yes | planned |

### TextFormat

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| align | yes | yes | yes | yes |
| blockIndent | yes | yes | yes | yes |
| bold | yes | yes | yes | yes |
| bullet | yes | yes | yes | yes |
| color | yes | yes | yes | yes |
| font | yes | yes | yes | yes |
| indent | yes | yes | yes | yes |
| italic | yes | yes | yes | yes |
| kerning | yes | yes | yes | yes |
| leading | yes | yes | yes | yes |
| leftMargin | yes | yes | yes | yes |
| letterSpacing | yes | yes | yes | yes |
| rightMargin | yes | yes | yes | yes |
| size | yes | yes | yes | yes |
| tabStops | yes | yes | yes | yes |
| target | yes | yes | yes | yes |
| underline | yes | yes | yes | yes |
| url | yes | yes | yes | yes |
| clone | yes | yes | yes | yes |

### TextLineMetrics

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| ascent | yes | yes | yes | yes |
| descent | yes | yes | yes | yes |
| height | yes | yes | yes | yes |
| leading | yes | yes | yes | yes |
| width | yes | yes | yes | yes |
| x | yes | yes | yes | yes |

## openfl.ui

### Keyboard

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| capsLock | yes | yes | yes | yes |
| numLock | yes | yes | yes | yes |
| isAccessible | yes | ignored | ignored | ignored |

### Mouse

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| hide | yes | planned | yes | planned |
| show | yes | planned | yes | planned |

### Multitouch

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| inputMode | yes | partial | partial | partial |
| maxTouchPoints | yes | ignored | ignored | ignored |
| supportedGestures | yes | ignored | ignored | ignored |
| supportsGestureEvents | yes | ignored | ignored | ignored |
| supportsTouchEvents | yes | yes | yes | yes |

## openfl.utils

### ByteArray

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| bytesAvailable | yes | yes | yes | yes |
| endian | yes | yes | yes | yes |
| objectEncoding | yes | ignored | ignored | ignored |
| position | yes | yes | yes | yes |
| clear | yes | yes | yes | yes |
| compress | yes | no | yes | yes |
| deflate | yes | no | yes | yes |
| inflate | yes | yes | yes | yes |
| readBoolean | yes | yes | yes | yes |
| readByte | yes | yes | yes | yes |
| readBytes | yes | yes | yes | yes |
| readDouble | yes | yes | yes | yes |
| readFloat | yes | yes | yes | yes |
| readInt | yes | yes | yes | yes |
| readMultiByte | yes | yes | yes | yes |
| readShort | yes | yes | yes | yes |
| readUnsignedByte | yes | yes | yes | yes |
| readUnsignedInt | yes | yes | yes | yes |
| readUnsignedShort | yes | yes | yes | yes |
| readUTF | yes | yes | yes | yes |
| readUTFBytes | yes | yes | yes | yes |
| uncompress | yes | partial | yes | yes |
| writeBoolean | yes | yes | yes | yes |
| writeByte | yes | yes | yes | yes |
| writeBytes | yes | yes | yes | yes |
| writeDouble | yes | yes | yes | yes |
| writeFloat | yes | yes | yes | yes |
| writeInt | yes | yes | yes | yes |
| writeMultiByte | yes | yes | yes | yes |
| writeShort | yes | yes | yes | yes |
| writeUnsignedByte | yes | yes | yes | yes |
| writeUnsignedInt | yes | yes | yes | yes |
| writeUnsignedShort | yes | yes | yes | yes |
| writeUTF | yes | yes | yes | yes |
| writeUTFBytes | yes | yes | yes | yes |

### Timer

| Feature | <div class="text-center">Flash</div> | <div class="text-center">HTML5</div> | <div class="text-center">Native</div> | <div class="text-center">Native (Next)</div> |
| ------- |:----:|:----:|:----:|:----:|
| currentCount | yes | yes | yes | yes |
| delay | yes | yes | yes | yes |
| repeatCount | yes | yes | yes | yes |
| running | yes | yes | yes | yes |
| reset | yes | yes | yes | yes |
| start | yes | yes | yes | yes |
| stop | yes | yes | yes | yes |

_* Implemented using software rendering instead of hardware rendering_