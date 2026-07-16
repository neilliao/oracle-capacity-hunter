# oracle-capacity-hunter

每 15 分鐘自動嘗試在 Oracle Cloud (ap-tokyo-1) 建立一台 `VM.Standard.A1.Flex`（4 OCPU / 24GB，Always Free）機器，直到搶到容量為止。

- 成功後會在這個 repo 開一個 Issue 通知（GitHub 會寄信到你的帳號信箱），並自動關閉這個排程。
- 想手動觸發一次：Actions 分頁 → Hunt Oracle A1.Flex Capacity → Run workflow。
- 想停止：Actions 分頁把這個 workflow 停用，或直接刪除這個 repo。
