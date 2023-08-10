Một số template hay dùng:

- Công thức:

Inline (xuất hiện trong các đoạn văn dùng) cặp ```$...$```

Nếu đánh công thức riêng một dòng không đánh số:
```
\begin{equation*}

\end{equation*}
```
Nếu đánh công thức riêng một dòng có đánh số:
```
\begin{equation}

\end{equation}
```
- Chèn ảnh

Dùng template:
```
\begin{figure}[h!]
        \centering
        \includegraphics[width=0.6\textwidth]{figures/1.png} % độ rộng ảnh bằng 0.6 độ rộng tối đa của một dòng
        \caption{Biểu đồ tần suất của các trường like, where, freq, busy, educ, sex} % caption của ảnh
        \label{fig:1} % label của ảnh dùng để reference ảnh. Trong bài viết có chỗ nào cần nói "tại hình 1" thì viết "tại hình \ref{fig:1}"
\end{figure}
```

- Chèn bảng biểu:

```
\begin{table}[h!]
    \centering
    \caption{So sánh các bộ giải phương trình SDE đảo ngược thời gian khác nhau trên tập CIFAR-10.}
    \begin{tabular}{|c| c |c |c|} 
     \hline
     Col1 & Col2 & Col2 & Col3 \\ [0.5ex] 
     \hline\hline
     1 & 6 & 87837 & 787 \\ 
     \hline
     2 & 7 & 78 & 5415 \\
     \hline
     3 & 545 & 778 & 7507 \\
     \hline
     4 & 545 & 18744 & 7560 \\
     \hline
     5 & 88 & 788 & 6344 \\ [1ex] 
     \hline
    \end{tabular}
    }
    \label{tab:1}
\end{table}
```

- Một số lưu ý khi đánh công thức:

Các đại lượng vô hướng là chữ in thường. Ví dụ $a, n , N$
Các đại lượng vector 1 chiều là chữ thường in đậm. Ví dụ $\bold{a}, \bold{e}, \bold{z}$.
Các ma trận là chữ hoa in đậm. Ví dụ $\bold{A}, \bold{B}$

Để viết in đậm trong latex dùng ```\bold{A}``` thành $\bold{A}$