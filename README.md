# cypress
- 搜尋    * ID(# )   *class(. ) *name([ ])
```
.get('  ') 
```
- 點擊被隱藏的屬性          
```
.click({ force: true });
```
- 過濾器        
```
.then((xhr) => { });
```
- 選取關鍵字 
```
.contains('class','data')
```
- 選擇選單內容      
```
.select(data)
```
- 順位
```
.eq()
```
- 等待
```
.wait();
```
- 嚴格判斷
```
.should('be.visible')
```
- 找到外框
```
.within(() => { })
```
- 輸入x值加enter動作     
```
.type('x{enter}')
```
刪除內容     
```
.clear()
```
