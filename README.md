# flask_note
My Flask Note

### 調試模式

雖然run()方法適用於啟動本地的開發服務器，但是你每次修改代碼後都要手動重啟它。這樣並不夠優雅，而且Flask可以做到更好。如果你啟用了調試支持，服務器會在代碼修改後自動重新載入，並在發生錯誤時提供一個相當有用的調試器。

有兩種途徑來啟用調試模式。一種是直接在應用對像上設置:

app.debug = True

app.run ()

另一種是作為run 方法的一個參數傳入:

app.run(debug=True)

