# AndEngineScriptingExtensionGenerator

## Usage

```
-in-java-root /Users/ngramlich/Workspace/gdk/graphic_engines/AndEngine/AndEngine/src
-in-javabin-root /Users/ngramlich/Workspace/gdk/graphic_engines/AndEngine/AndEngine/bin
-gen-java-root /Users/ngramlich/Workspace/gdk/graphic_engines/AndEngine/AndEngineScriptingExtension/src
-gen-cpp-root /Users/ngramlich/Workspace/gdk/graphic_engines/AndEngine/AndEngineScriptingExtension/jni/src
-gen-java-formatter jalopy
-gen-java-class-suffix ProxyX
-gen-cpp-class-suffix Proxy
-gen-method-include getX
-gen-method-include getY
-gen-method-include setX
-gen-method-include setY
-gen-method-include onAttached
-gen-method-include onDetached
-gen-method-include onAreaTouched
-class org.andengine.engine.handler.IUpdateHandler
-class org.andengine.engine.handler.IDrawHandler
-class org.andengine.engine.camera.Camera
-class org.andengine.engine.camera.hud.HUD
-class org.andengine.entity.scene.ITouchArea
-class org.andengine.entity.scene.IOnAreaTouchListener
-class org.andengine.entity.scene.IOnSceneTouchListener
-class org.andengine.input.touch.TouchEvent
-class org.andengine.util.adt.transformation.Transformation
-class org.andengine.util.color.Color
-class org.andengine.util.IDisposable
-class org.andengine.util.IMatcher
-class org.andengine.opengl.util.GLState
-class org.andengine.opengl.shader.ShaderProgram
-class org.andengine.opengl.shader.source.IShaderSource
-class org.andengine.opengl.vbo.IVertexBufferObject
-class org.andengine.opengl.vbo.VertexBufferObjectManager
-class org.andengine.opengl.vbo.DrawType
-class org.andengine.opengl.texture.region.ITextureRegion
-class org.andengine.entity.Entity
-class org.andengine.entity.IEntity
-class org.andengine.entity.IEntityMatcher
-class org.andengine.entity.scene.background.IBackground
-class org.andengine.entity.primitive.Rectangle
-class org.andengine.entity.primitive.vbo.IRectangleVertexBufferObject
-class org.andengine.entity.primitive.Line
-class org.andengine.entity.primitive.vbo.ILineVertexBufferObject
-class org.andengine.entity.scene.Scene
-class org.andengine.entity.scene.CameraScene
-class org.andengine.entity.sprite.Sprite
-class org.andengine.entity.sprite.vbo.ISpriteVertexBufferObject
-class org.andengine.entity.shape.IShape
-class org.andengine.entity.shape.Shape
-class org.andengine.entity.shape.IAreaShape
-class org.andengine.entity.shape.RectangularShape
```