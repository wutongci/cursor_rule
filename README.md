# cursor_rule


cursor/rule 配置

```
.cursor/
└── rules/
    ├── coding_style.mdc
    ├── general.mdc
    ├── generated_files.mdc
    ├── requirements.mdc
    ├── testing.mdc
    └── task_management.mdc
```
记忆银行

```
memory-bank/
├── open/                
│   └── {task-id}/      
│       ├── activeContext.md  # 任务特定的上下文
│       ├── .plan           # 任务计划 (可选)
│       └── ...             # 其他与任务相关的文件
├── done/               
│   └── {task-id}/      
│       ├── activeContext.md  # 任务特定的上下文 (归档)
│       └── ...             # 其他与任务相关的文件 (归档)
├── productContext.md
├── projectbrief.md
├── progress.md
├── systemPatterns.md
├── techContext.md
├── testingStrategies.md
├── features/           
│   └── ...
├── integrations/       
│   └── ...
├── api/                
│   └── ...
└── deployment/         
    └── ...
```