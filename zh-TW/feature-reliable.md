## 高度可靠的傳輸

雖然 UDP 不提供可靠的傳輸，但 QUIC 在基於 UDP 時增加了一層帶來可靠性的層。
它提供了封包重傳，擁塞控制，調整傳輸節奏（ pacing ）及其他一些 TCP 中存在的特性。

只要連接沒有中斷，從 QUIC 一端傳輸的資料都會出現在另一端，只是時間早或晚的問題。
