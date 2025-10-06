## Hi there 👋
## 📊 GitHub 统计
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=zxcvbnmkj&show_icons=true&theme=radical&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&cache_seconds=1800&random=123)

![ 语言统计 ](https://github-readme-stats.vercel.app/api/top-langs/?username=zxcvbnmkj&layout=compact&theme=gruvbox)
## 🛠 技术栈
```python
class AIEngineer:
    def __init__(self):
        self.skills = {
            # 深度学习与AI工程
            "deep_learning": {
                "frameworks": ["PyTorch", "TensorFlow", "Keras"],
                "model_architectures": ["CNN", "RNN/LSTM", "Transformer", "BERT系列"],
                "training_optimization": ["混合精度训练", "梯度累积", "学习率调度"],
                "distributed_training": ["DeepSpeed", "Hadoop", "Spark", "多GPU并行"],
                "model_compression": ["量化(INT8/FP16)", "剪枝", "知识蒸馏", "模型轻量化"]
            },
            
            # 机器学习与算法
            "machine_learning": {
                "learning_paradigms": [
                    "零样本学习(Zero-shot)", 
                    "少样本学习(Few-shot)",
                    "半监督学习", 
                    "弱监督学习",
                    "预训练-微调Pipeline"
                ],
                "advanced_techniques": [
                    "检索增强生成(RAG)",
                    "提示工程", 
                    "模型微调策略",
                    "多模态学习"
                ],
                "model_deployment": ["ONNX", "TensorRT", "模型服务化", "边缘部署"]
            },
            
            # 全栈开发
            "fullstack_development": {
                "frontend": ["Vue生态系统", "Node.js", "TypeScript", "响应式Web开发"],
                "backend": ["FastAPI", "SpringBoot", "Flask", "RESTful架构"],
                "databases": ["MySQL", "Redis", "SQLite", "SQL Server", "数据库优化"],
                "devops": ["Docker", "Linux系统运维", "CI/CD", "Nginx", "系统监控"]
            },
            
            # 编程语言
            "programming_languages": {
                "primary": ["Python", "JavaScript", "Java"],
                "secondary": ["SQL", "Shell", "HTML/CSS"]
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

**🤖 深度学习与AI工程**

![PyTorch](https://img.shields.io/badge/PyTorch-Expert-red)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Advanced-orange)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-Intermediate-yellow)
![模型压缩](https://img.shields.io/badge/模型压缩-Expert-red)

**🔬 机器学习算法**

![少样本学习](https://img.shields.io/badge/少样本学习-Advanced-orange)
![RAG](https://img.shields.io/badge/RAG-Intermediate-yellow)
![Transformer](https://img.shields.io/badge/Transformer-Expert-red)

**💻 全栈开发**

![Vue](https://img.shields.io/badge/Vue-Advanced-orange)
![FastAPI](https://img.shields.io/badge/FastAPI-Expert-red)
![SpringBoot](https://img.shields.io/badge/SpringBoot-Intermediate-yellow)
![Docker](https://img.shields.io/badge/Docker-Advanced-orange)

**🗄️ 数据库与运维**

![MySQL](https://img.shields.io/badge/MySQL-Expert-red)
![Redis](https://img.shields.io/badge/Redis-Advanced-orange)
![Linux](https://img.shields.io/badge/Linux-Expert-red)

## 💼 实战经验摘要

- **大规模模型训练**: 使用DeepSpeed和分布式策略完成亿级参数模型训练
- **边缘AI部署**: 通过量化和剪枝技术，在资源受限设备实现模型高效推理
- **RAG系统构建**: 设计并实现检索增强生成系统，提升LLM应用效果
- **全链路交付**: 从算法设计到前后端开发，完成多个AI应用完整交付
- **性能优化**: 数据库优化、缓存策略、模型推理加速等系统性调优
