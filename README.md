# GO编译流程

# 背景

GO属于静态语言，需要编译才能运行，因为计算机只能实别二进制机器码。GO编译过程分为前端和后端，编译前端主要有词法分析、语法分析、类型检查及语义分析，编译后端主要有中间码生成、代码优化及机器码生成。  
![][image1]

# 详细文件查看GC.PDF，也可以在线查看 https://docs.google.com/document/d/1cMfYz6-xv-IbCqUHolR_GzBdXAMXeuHCtQbMwJDxSjM/edit?usp=sharing