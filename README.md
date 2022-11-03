# merge_sort_projesi
# [16,21,11,8,12,22] 
#  1) Yukarıdaki dizinin merge sort türüne göre aşamaları:
#     [16,21,11,8,12,22] -> [16,21,11] ve [8,12,22] olarak ayrılsın. 
#     [16,21,11] -> [16,21] ve [11] olarak ayrılsınlar. [8,12,22] zaten düzgün dizilmiştir
#     [16,21] -> [16] , [21] ; [11] -> [11] olur ve sonuç olarak [11,16,21] şeklinde birleşirler.
#     [11,16,21] ve [8,12,22] karşılaştırılarak birleştirilirse -> [8,11,12,16,21,22] olur.
#  2) Yukarıdaki dizinin Big-O gösterimi; sıralama,eleman sayısı (n olsun) sürekli 2'ye bölünerek incelendiğinden
#     2^x = n -> x = logn olduğundan Big-O gösterimi "O(nlogn)" şeklindedir. 
