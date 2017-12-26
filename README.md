# vagrant
Create VM on vagrant file
# Команды
vagrant box add image_name - Добавить образ ВМ
vagrant box add ubuntu/trusty64 - Образ с убунту
vagrant box add centos/7 -Образ с CentOS7
vagrant box list - просмотр скачанных образов
vagrant init image_name - создать ВМ
vagrant up - запустить ВМ
vagrant ssh - залогиниться в ВМ по ssh
vagrant global-status - Просмотр ВМ и их состояние
vagrant global-status --prune - Удалили ВМ из VB а в global-status осталась, лечится так.
vagrant suspend VM_ID - ВМ на паузе
vagrant resume VM_ID - ВМ из паузы
vagrant halt VM_ID/vagrant up VM_ID - остановка/запуск ВМ
vagrant destroy - удаление ВМ
