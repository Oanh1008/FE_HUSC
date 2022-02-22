

Layout cho web

Float : is used to pull a element to left or to right of webpage


* rules of Float
    - khi 1 pt đc thiết lập  (left or right) thì: 
        - nó sẽ đc bắt đầu hiển thị ở hàng phía trên nếu hàng trên đủ chổ trống
        - hiển thị new column nếu pre column k có đủ chổ
        - if an element is float, but pre element is not put float, so it will show bottom column
    
    - Tác động xấu " float"
        - 1/tràn dữ liệu nếu ra khỏi vùng chưa nó
        giải quyết: bổ sung thuộc tình overfloat:auto

        - 2/ ảnh hưởng next element
            if element is FLoat , mà next ele  k có float thì next ele sẽ bị tác động "XẤU"

            use: css ---  clear:both
