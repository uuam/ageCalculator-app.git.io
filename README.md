# Forntend Mentor Challenge - Age calculator app [🔗](https://uuam.github.io/ageCalculator-app.github.io/)
輸入出生年月日，轉換為出生年齡

[前往：生日轉換器](https://uuam.github.io/ageCalculator-app.github.io/)

## 特點
這個專案具有以下一些特點：
1. 使用 TypeScript：使用 TypeScript 進行開發，提供了靜態型別檢查和更好的程式碼可讀性。
2. 模塊化開發：這個專案使用模塊化開發的方式，將程式碼分解為多個模塊或組件，提供了更好的程式碼組織和可維護性。
3. 整合第三方套件：專案整合了一些常用的第三方套件，例如 dayjs 時間處理套件，解決複雜的時間設置。
4. 使用 Webpack 打包工具：專案使用 Webpack 作為模組打包工具，用於處理資源的載入、壓縮和打包，並提供了開發和生產環境的配置。
5. 響應式設計：這個專案採用了響應式設計，使網頁在不同的設備和螢幕尺寸下都能提供良好的使用體驗。
6. 動畫效果：輸入正確的年月日後，會有數字累加的動畫效果。

## 難題
在開發這個專案的過程中，我遇到了一些挑戰，包括：
1. 輸入限制：由於年份(平、閏年)或月份不同，而影響日期輸入的限制，並且需跳出錯誤提示。
2. 語言轉換：為了代碼的嚴謹，從使用JavaScript開發，改為使用TypeScript，邊學邊寫的挑戰難度特別高。
3. Promise異步操作：首次將promise應用至代碼中。
4. 使用dayjs套件：雖然使用dayjs套件解決了許多時間上的設定，但若要轉換為date就有時差的問題存在。


## 其他
挑戰連結：[Challenge link](https://www.frontendmentor.io/challenges/age-calculator-app-dF9DFFpj-Q)
