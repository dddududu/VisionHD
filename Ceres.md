ceres::Solve(options,problems,summary)
配置优化选项、定义优化问题、总结报告

1.首先定义优化问题problem
  ①构建一个结构体or类，重写operator（），定义残差项residual
