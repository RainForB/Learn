### 内置字体
```csharp
Font BuildInFont = Resources.GetBuiltinResource<Font>("Arial.ttf");
```

### 内置Material
```csharp
Material mat = new Material(Shader.Find("Sprites/Default"));
```

### 自定义Material
```csharp
Material mat = new Material(Shader.Find("Custom/YourCustomShader"));    // directory name "Custom" depends on your shader
```

```
Shader "Custom/YourCustomShader" {
  Properties {
```
