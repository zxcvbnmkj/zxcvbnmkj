## Hi there 👋
## 📊 GitHub 统计
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=zxcvbnmkj&show_icons=true&theme=radical&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&cache_seconds=1800&random=123&rank_icon=github)

![ 语言统计 ](https://github-readme-stats.vercel.app/api/top-langs/?username=zxcvbnmkj&layout=compact&theme=gruvbox&cache_seconds=1800&random=123)
## 🛠 技术栈
```python
class AIEngineer:
    def __init__(self):
        self.skills = {
            # 深度学习
            "deep_learning": {
                "frameworks": ["PyTorch", "TensorFlow", "Keras"],
                "model_architectures": ["CNN", "RNN", “LSTM”, "Transformer", "BERT"],
                "training_optimization": ["混合精度训练", "梯度累积", "学习率调度策略"],
                "distributed_training": ["DeepSpeed", "Hadoop", "Spark"],
                "model_compression": ["量化(INT8/FP16)", "剪枝", "知识蒸馏"]
            },
            
            "learning_strategy": {
                "learning_paradigms": [
                    "零样本学习(Zero-shot)", 
                    "少样本学习(Few-shot)",
                    "半监督学习", 
                    "弱监督学习",
                ],
                "advanced_techniques": [
                    "检索增强生成(RAG)",
                    "提示工程", 
                    "模型微调策略",
                    "多模态学习"
                ]
            },
            
            # 全栈开发
            "fullstack_development": {
                "frontend": ["Vue", "Node.js", "TypeScript"],
                "backend": ["FastAPI", "SpringBoot"],
                "databases": ["MySQL", "Redis", "SQLite", "SQL Server"],
                "devops": ["Docker", "Linux", "Nginx"]
            },
            
            # 编程语言
            "programming_languages": {
                "primary": ["Python", "C", "C++", "Java"],
                "secondary": ["SQL", "Shell", "HTML", "CSS"]
            }
        }
    
    def get_tech_stack(self):
        """返回完整技术栈"""
        stack = []
        for category, skills in self.skills.items():
            for subcategory, items in skills.items():
                stack.extend(items)
        return stack
    
    def describe_experience(self):
        return {
            "ai_engineering": "具备从模型设计、训练优化到生产部署的完整工程能力",
            "large_scale_training": "拥有大规模模型分布式训练实战经验",
            "model_compression": "精通模型压缩技术，实现资源受限场景高效部署",
            "fullstack_delivery": "具备完整的Web应用及小程序开发交付能力"
        }

# 实例化
engineer = AIEngineer()
print("🎯 技术专长:", engineer.describe_experience())
print("🚀 技术栈:", engineer.get_tech_stack())
```
## 🎯 核心技术领域

**🤖 深度学习**

![PyTorch](https://img.shields.io/badge/PyTorch-Expert-red)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Advanced-orange)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-Intermediate-yellow)
![Transformer](https://img.shields.io/badge/Transformer-Expert-red)

**🔬 学习算法**

![少样本学习](https://img.shields.io/badge/少样本学习-Advanced-orange)
![RAG](https://img.shields.io/badge/RAG-Intermediate-yellow)

**💻 全栈开发**

![Vue](https://img.shields.io/badge/Vue-Advanced-orange)
![FastAPI](https://img.shields.io/badge/FastAPI-Expert-red)
![SpringBoot](https://img.shields.io/badge/SpringBoot-Intermediate-yellow)
![Docker](https://img.shields.io/badge/Docker-Advanced-orange)

**🗄️ 操作系统与数据库**

![Linux](https://img.shields.io/badge/Linux-Expert-red)
![MySQL](https://img.shields.io/badge/MySQL-Expert-red)
![Redis](https://img.shields.io/badge/Redis-Advanced-orange)


## 💼 实战经验

- **大模型微调**: 使用DeepSpeed和分布式策略完成参数过亿大模型的微调
- **模型部署**: 通过量化和剪枝技术，在资源受限设备实现模型高效推理
- **RAG系统构建**: 设计并实现检索增强生成系统，提升LLM应用效果，减少幻觉
- **前后端开发**: 从算法设计到前后端开发，将模型封装为能够可视化使用的系统
- **性能优化**: 数据库优化、缓存策略、模型推理加速等系统性调优
