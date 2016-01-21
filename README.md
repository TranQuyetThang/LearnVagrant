# LearnVagrant

##Yêu cầu:  
- Cài đặt vagrant          https://www.vagrantup.com/downloads.html  
- Cài đặt vitural box      https://www.virtualbox.org/wiki/Downloads
- Cài đặt git-bash         http://git-scm.com/download/win
  
  
##Các bước khởi tạo:
B1: Nạp 1 box (gói hệ điều hành, có thể tìm gói trong https://atlas.hashicorp.com/boxes/search?utm_source=vagrantcloud.com&vagrantcloud=1 ) 
vagrant box add [chef/centos-6.5-i386] (tìm tên gói muốn thêm download về  )
có thể sẽ yêu cầu chọn máy ảo phù hợp.  
B2: Khởi tạo máy ảo  
vagrant init [centos65] (tên box)
