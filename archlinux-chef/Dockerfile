# archlinux with base-devel and chef client from  Rubygems

FROM shingonoide/archlinux-devel:201502122155
RUN pacman -Sy --needed --noconfirm rubygems
RUN gem install --no-document --minimal-deps --conservative --no-user-install chef
