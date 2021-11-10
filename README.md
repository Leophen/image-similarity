# image-similarity

## 功能

图片颜色相似度判断。

## 使用

```js
import './color-thief.js'

imageSimilarity(src).then((similarity) => {
  // 0 极度相似
  // 1 相似
  // 2 不太相似
  // 3 不相似
  // 4 差异较大
  if (similarity === 0) {
    console.log('视觉色彩极度相似')
  } else if (similarity === 1) {
    console.log('视觉色彩相似')
  } else if (similarity === 2) {
    console.log('视觉色彩不太相似')
  } else if (similarity === 3) {
    console.log('视觉色彩不相似')
  } else {
    console.log('视觉色彩差异较大')
  }
})
```
