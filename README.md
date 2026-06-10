pdf-word/
├── server.js          # Express 服务器（端口 3000）
├── converter.js       # 转换核心（文本提取 / OCR / 生成 docx）
├── package.json       # 依赖配置
├── .gitignore         # 忽略 node_modules/ uploads/ 等
├── tessdata/
│   └── eng.traineddata    # 英文 OCR 语言数据
├── public/
│   ├── index.html     # 页面
│   ├── styles.css     # 样式
│   └── app.js         # 前端逻辑
├── uploads/           # 临时上传文件（gitignore 忽略）
├── outputs/           # 输出目录（gitignore 忽略）
└── work/              # 工作目录（gitignore 忽略）
