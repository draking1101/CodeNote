# React Native
## <span style='color:#4ea5da'>React-Native環境架設</pspan>
### <span style="font-size:24px"><a href='https://nodejs.org/en' alt='連結失效，請通知嘯天' style="color:#dfc5ae">安裝node.js</a></span>  
* 推薦用nvm(node版本控制工具)安裝   ，方便未來變更使用的node版本
  * <span href='https://www.casper.tw/development/2022/01/10/install-nvm/' target='_blank' style='color:#ccccff' >nvm安裝教學 by   卡斯柏</span>

### <span style="font-size:24px;color:#dfc5ae">安裝模擬器</span>  
* Android
    * 使用<a href='https://developer.android.com/studio?hl=zh-tw'  alt='連結失效，請通知嘯天' style='color:#ccccff'>Android Studio</a></br>
* IOS
    * 使用<a href='https://developer.apple.com/xcode/Xcode'  alt='連結失效，請通知嘯天' style='color:#ccccff'>Xcode   </a></br>

### <span style="font-size:24px;color:#dfc5ae">環境變數設定</span>
* Android 
  * 變數名稱:ANDROID_HOME
  * 變數路徑:C:\User\user\AppData\Local\Android\sdk
  * 具體方式參考<a href='https://reactnative.dev/docs/environment-setup?guide=native'  alt='連結失效，請通知嘯天' style='color:#ccccff'>官方教學</a></br>

---

# <span style='color:#4ea5da'>常見指令</span>
## <span style="font-size:24px;color:#dfc5ae">建立專案</span>
* 如果曾用react-native-cli建立專案,請移除以避免不可預期的問題，程式碼如下
  * ```yaml
    npm uninstall -g react-native-cli @react-native-community/cli
    ```
* 建立最新版本專案(推薦)，程式碼如下
  * ```markdown
    npx react-native@latest init <Project_name>
    ```
* 建立指定版本專案，程式碼如下
  * ```markdown
    npx react-native@X.XX.X init <Project_name>  --version X.XX.X
    ``` 

## <span style="font-size:24px;color:#dfc5ae">套件安裝</span>
* 安裝套件 - 具體指令要看套件的網站說明
  * ```markdown
    npm install <package_name>
    ``` 
* 刪除套件
  * ```markdown
    npm uninstall <package_name>
    ```
* 變更套件後，記得重新啟動並清除緩存
  *   ```markdown
      npx react-native start --reset-cache
      ``` 
## <span style="font-size:24px;color:#dfc5ae">程式碼測試</span>
* 啟動伺服器模擬
  *   ```markdown
      npm start
      ```
* 啟動後按對應按鍵
  * i - run on iOS
  * a - run on Android
  * d - open Dev Menu
  * r - reload app  ( <span style='color:#bce1e2'>重新加載，如果畫面沒更新，連按兩次R來更新</span> )




# <span style='color:#4ea5da'>套件</span>

## <span style='color:#dfc5ae'>Navigation</span>
* 功能 : 頁面導引
* 官網 : <a href='https://reactnavigation.org/docs/getting-started' target='_blank' style='color:#ccccff'>Navigation</a>
* 相關套件
  * navigation/bottom-tabs
    * ```markdown
      npm install @react-navigation/bottom-tabs
      ```
  * navigation/native
    * ```markdown
      npm install @react-navigation/native
      ```
  * navigation/native-stack
    * ```markdown
      npm install @react-navigation/native-stack
      ```
  * react-native-screens react-native-safe-area-context
    * ```markdown
      npm install react-native-screens react-native-safe-area-context
      ```


## <span style='color:#dfc5ae'>Switch</span>
* 功能 : 切換按鈕 (登入Sign in/Sign up可用)
* 官網 : <a href='https://reactnative.dev/docs/switch' target='_blank' style='color:#ccccff'>Switch</a>