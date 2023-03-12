# Đề làm trong 30p

Cho một hàm
```typescript
export default function checkChangeTeam(player: number, goals: number[]): "Yes" | "No" {
  
}
```

* `player`: số lượng cầu thủ trong 1 đội bóng
* `goals`: Mỗi cầu thủ sẽ mặc một cái áo, trên áo sẽ ghi một con số tuơng ứng với số bàn thắng mà người đó ghi được, mảng `goals` đại diện cho các **loại** bàn thắng.
* Các cầu thủ đứng cạnh nhau có thể đổi chỗ cho nhau;
* Tất cả các cầu thủ ban đầu sẽ đều thuộc `Team A`.
* Khi 2 cầu thủ `Team A` đổi chỗ cho nhau họ sẽ chuyển sang `Team B`
* Khi một cầu thủ `Team A` đổi chỗ cho 1 cầu thủ `Team B` thì họ sẽ đổi `A` <=> `B`, `B` <=> `A`
* Khi 2 cầu thủ `Team B` đổi chỗ cho nhau thì họ sẽ chuyển sang `Team A`

Nhiệm vụ của bạn là kiểm tra xem có thể sắp xếp các cầu thủ theo thứ tự giảm dần bằng cách hoán vị và sau đó tất cả các cầu thủ đều thuộc team B không.

Ví dụ:

Test case 1:
`player`: 2
`goals`: [4, 6]
return "Yes"

Test case 2:
`player`: 4
`goals`: [4, 2, 9]
Có một cầu thủ không rõ, vậy các thường hợp có thể sảy ra là [4,4,2,9], [4,2,2,9], [4,2,9,9],
return: "No"
