# 도커 호스트 설정

## 가상머신 메모리제한 해제

### 방법1

- grep vm.max_map_count /etc/sysctl.conf
- vm.max_map_count=262144

### 방법2

sysctl -w vm.max_map_count=262144
