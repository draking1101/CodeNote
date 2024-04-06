# <span style='color:#4ea5da'>React</span>
* <a href='https://tw.alphacamp.co/blog/react-beginner' target='_blank' style='color:#ccccff'>React是什麼?</a>
# <span style='color:#4ea5da'>伺服器模擬</span>
  * 啟動伺服器
    *   ```yaml
        npm start
        ```
  * 啟動伺服器並清除緩存 (有變更套件時使用)
    *   ```yaml
        npm start -- --reset-cache    
        ```

# <span style='color:#4ea5da'>圖片及CSS引入方法</span>
  * CSS
    *   ```yaml
        import './App.css';
        ```
  * 圖片
    *   ```yaml
        <img src={require('./img/background.jpg')} alt="Background"/>
        ``` 


# <span style='color:#4ea5da'>屬性標籤</span>
  ## <span style='color:#dfc5ae'>模糊 </span>   
    *   ```yaml
        backdrop-filter: blur(5px)
        ```
    * 元素本身無模糊效果，他是讓透過此元素看到的後面元素成模糊效果  


# <span style='color:#4ea5da'>套件</span>
## <span style='color:#dfc5ae'>react-router</span>
* 功能 : 導引頁面
* 官網 : <a href='https://reactrouter.com/en/main' target='_blank' style='color:#ccccff'>React Router</a>