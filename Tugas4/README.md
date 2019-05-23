## Final Project Network Programming 2019

### Anggota Kelompok
- Ariiq Firanda Naufal 05111640000083
- Fariz Putra Dandi 05111640000140
- Khairunnisa' Rahma Mardiyani 05111640000187

### Assignment
- Implementasikan applikasi chat dengan code progjar4 sebagai dasar
- Tambah fitur:
    - Logout
    - Group chat
    - Send/Receive File/Image
- Implementasikan juga GUI (Optional)

### Protocol Dasar
- `auth [username] [password]`
- `send [username_to] [message]`
- `inbox`

### New Protocol
- [x] `logout`
- [x] `create_group [group_name]`
- [x] `join_group [group_name]`
- [x] `send_group [group_name] [message]`
- [x] `inbox_group [group_name]`
- [x] `leave_group [group_name]`
- [x] `sendfile [username_to] [file]`
- [x] `recvfile [file]`
- [x] `sendfile_group [group_name] [file]`
- [x] `recvfile_group [group_name] [file]`
