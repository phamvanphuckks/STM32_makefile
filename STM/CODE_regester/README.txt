liên quan đến những file cần có thì có thể phân loại thành 3 nhóm file chính:
1. Linker file
2. Startup code file
3. App file: tên này thì mình tạm gọi là vậy. Những file này sẽ chứa những gì bạn viết cho chương trình bạn muốn. Nó có thể C file hoặc ASM file.

Còn đề cập đến file nào qua trọng nhất thì mình thấy đó vẫn là App file thôi. Bởi nó quyết định cách MCU sẽ chạy theo một kịch bản như thế nào. Và tạo ra sự khác biệt giữa chương trình này với chương trình kia.

Về Mapfile sẽ chữa những thông tin về chương trình bạn sẽ allocate những thành phần như function/ global variable/ heap/ stack/ và một số vùng người dùng tự định nghĩa. Sẽ ở đâu (địa chỉ nào) trong phân vùng bộ nhớ của MCU.