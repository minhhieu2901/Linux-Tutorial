# Luồng dữ liệu trong Linux

## 1. Các luồng dữ liệu

- ***Standard input/standard in/stdin***: Dữ liệu truyền vào để process xử lý. Có thể là dữ liệu nhập từ bàn phím, tập tin, hay output của process khác.

- ***Standard output/standard out/stdout***: Kết quả sau khi xử lý, thường là kết quả xuất ra màn hình (terminal). Hoặc có thể ghi vào tập tin, hoặc truyền cho process khác xử lý tiếp.

- ***Standard error/stderr***: Lỗi khi process xử lý, thường cũng xuất ra màn hình hoặc có thể ghi vào tập tin, hoặc truyền cho process khác xử lý.

<img src="https://i0.wp.com/trungquan710.com/wp-content/uploads/2015/07/linux_process_data_streams.png">


## 2. Thao tác điều khiển Output trong Linux

**Ghi Output ra file**

```
root@ubuntu:/tmp# ls -l >outputtest.log
root@ubuntu:/tmp# cat outputtest.log
total 28
-rw-r--r-- 1 root root    0 Aug 12 20:50 outputtest.log
drwx------ 3 root root 4096 Aug 12 19:59 systemd-private-30439cce77574714bb38e03822fbf50b-systemd-networkd.service-KLsRPt
drwx------ 3 root root 4096 Aug 12 19:59 systemd-private-30439cce77574714bb38e03822fbf50b-systemd-resolved.service-QCT3T9
drwx------ 3 root root 4096 Aug 12 19:59 systemd-private-30439cce77574714bb38e03822fbf50b-systemd-timesyncd.service-mTRMmR
drwxrwxrwt 2 root root 4096 Aug 12 19:59 VMwareDnD
drwx------ 2 root root 4096 Aug 12 19:59 vmware-root
drwx------ 2 root root 4096 Aug 12 19:59 vmware-root_905-4013330159
-rw-r--r-- 1 root root  208 Aug 12 20:47 xyz.log
```



















## Refrences - Special thanks !

https://trungquan710.com/linux/luong-du-lieu-doi-voi-linux-process.html