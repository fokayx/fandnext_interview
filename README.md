# 2023 fandnext interview

## HTML, CSS & Javascript

- 可自由調整更改 HTML 結構
- CSS：麻煩使用 TailwindCSS
- JavaScript：麻煩使用純 Javascript，不使用其他 library

1. 640px 以上的螢幕寬度 checkbox font-size 設為 `text-xl`，不滿 640px font-size 設為 `text-sm`
  - Example screen width 320px：`text-sm`

  ![IMAGE](resources/93DCC1C36C57C7592CC4254A6AD3FED7.jpg)

  - Example screen width 820px：`text-xl`

  ![IMAGE](resources/0CB989F781B8EE98585C95FA36BE8EC4.jpg)

2. checkbox 新增 checked 狀態樣式

  - default 狀態

  ![IMAGE](resources/73E072ACC371BAA073FE6CF77685241A.jpg)

  - checked 狀態
    - border color: `border-blue-700`
    - text color: `text-blue-700`

  ![IMAGE](resources/3C408CE5986E8289143A9E3820424B6D.jpg)

3. 按鈕新增 hover 效果：background color: `bg-slate-700`

  ![IMAGE](resources/13DE9987F76B568A8EAEF41F78338EB0.jpg)

4. 用 checkbox 控制 button 的狀態和錯誤訊息顯示

  - checked status
    - button status enabled
    - add button enabled class: `btn-enabled`
    - hide error message：`check checkbox`

  ![IMAGE](resources/3C408CE5986E8289143A9E3820424B6D.jpg)

  - unchecked status
    - button status disabled
    - add button disabled class: `btn-disabled`
    - show error message：`check checkbox`

   ![IMAGE](resources/55B042FACCDBD2ECC1FC7114D0C096AA.jpg)

