import tkinter as tk
import time

def update_time():
    
    # 現在の時刻を文字列で取得 (例: 12:30:45)
    current_time = time.strftime("%H:%M:%S")

    # ラベルの表示を更新
    label.config(text=current_time)

    # 1000ミリ秒(1秒)後に再度この関数を呼ぶ
    label.after(1000, update_time)

# メインウィンドウの設定
root = tk.Tk()
root.title("時計")

# 時計を表示するラベルのデザイン
label = tk.Label(root, font=("Helvetica", 72), bg="black", fg="cyan")
label.pack(anchor="center")

# 最初の更新を開始
update_time()

# 画面を表示し続ける
root.mainloop()
