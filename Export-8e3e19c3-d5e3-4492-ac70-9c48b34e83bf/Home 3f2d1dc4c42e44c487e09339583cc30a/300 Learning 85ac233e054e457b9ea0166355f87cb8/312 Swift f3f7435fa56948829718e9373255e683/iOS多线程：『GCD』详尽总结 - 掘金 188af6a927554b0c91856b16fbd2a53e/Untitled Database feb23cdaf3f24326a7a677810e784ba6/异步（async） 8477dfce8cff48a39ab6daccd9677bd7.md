# 异步（async）

死锁卡住不执行: 有开启新线程（1 条），串行执行任务
死锁卡住不执行 1: 有开启新线程（1 条），串行执行任务
没有开启新的线程，串行执行任务: 有开启新线程，并发执行任务
没有开启新线程，串行执行任务: 有开启新线程，并发执行任务