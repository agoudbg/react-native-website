---
id: imagepickerios
title: 🚧 ImagePickerIOS
---

> **Deprecated.** Use one of the [community packages](https://reactnative.directory/?search=image+picker) instead.

# 文档

## 方法

### `canRecordVideos()`

```jsx
static canRecordVideos(callback)
```

---

### `canUseCamera()`

```jsx
static canUseCamera(callback)
```

---

### `openCameraDialog()`

```jsx
static openCameraDialog(config, successCallback, cancelCallback)
```

**参数：**

| 名称            | 类型     | Required | 说明       |
| --------------- | -------- | -------- | ---------- |
| config          | object   | No       | See below. |
| successCallback | function | No       | See below. |
| cancelCallback  | function | No       | See below. |

`config` is an object containing:

- `videoMode` : An optional boolean value that defaults to false.

`successCallback` is an optional callback function that's invoked when the select dialog is opened successfully. It will include the following data:

- `[string, number, number]`

`cancelCallback` is an optional callback function that's invoked when the camera dialog is canceled.

---

### `openSelectDialog()`

```jsx
static openSelectDialog(config, successCallback, cancelCallback)
```

**参数：**

| 名称            | 类型     | Required | 说明       |
| --------------- | -------- | -------- | ---------- |
| config          | object   | No       | See below. |
| successCallback | function | No       | See below. |
| cancelCallback  | function | No       | See below. |

`config` is an object containing:

- `showImages` : An optional boolean value that defaults to false.
- `showVideos`: An optional boolean value that defaults to false.

`successCallback` is an optional callback function that's invoked when the select dialog is opened successfully. It will include the following data:

- `[string, number, number]`

`cancelCallback` is an optional callback function that's invoked when the select dialog is canceled.
