1. 輸入token  
2. 使用上下鍵找到要的隧道
3. 按Enter
4. 按Tab
5. 按Enter
6. 大功告成!!!


https://cloudstudio.net/a/18486565505101824


運行在cloudstudio的preview.yml的配置方式

# .vscode/preview.yml
autoOpen: true # 打开工作空间时是否自动开启所有应用的预览
apps:
  - port: 3000 # 应用的端口
    run: chmod +x start.sh && ./start.sh # 应用的启动命令
    name: 防DDOS攻擊 # 应用名称
    description: 使用OPENFRP來防DDOS攻擊。 # 应用描述
    autoOpen: true # 打开工作空间时是否自动开启预览（优先级高于根级 autoOpen）
