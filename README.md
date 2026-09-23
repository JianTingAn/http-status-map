# URL HTTP 状态码地图

将站点 URL 清单映射为 2xx、3xx、4xx、5xx 等状态，帮助站长快速定位百度蜘蛛可能遇到的访问障碍。

## 核心功能
- 按状态码分类 URL
- 展示重定向目标和错误页面
- 统计目录级错误比例
- 支持 CSV 与 JSON 结果

## 使用
```powershell
python tool.py --demo
python tool.py --input sample.csv --json
```
重点检查 Sitemap 中的 404、循环跳转和服务器错误，确保公开页面返回稳定、明确的状态。

官网：https://jta.mobi  
QQ群：1039545483

## 许可证
MIT License
