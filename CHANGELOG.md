# Changelog
所有显著变更都会记录在此文档中。版本号遵循 [SemVer](https://semver.org/)。

## [Unreleased]
### Added
- （待补）未发布的新功能与改进
### Changed
- （待补）行为变化与重构
### Fixed
- （待补）缺陷修复

## [0.1.0] - 2025-09-07
### Added
- 初始公开版本：Streamlit 多标签页（今日计划、实时摄入、手动录入、报告、周期调度、导入/导出）
- BMR（Katch–McArdle / Mifflin–St Jeor）、TDEE、训练负荷（MET）建模
- 目标 %BW/week → 日赤字反推 + PID 微调
- EA（能量可用性）安全护栏与训练日碳水加成、碳水最小地板
- SQLite 持久化与四表 CSV 导入/导出
- 报告可视化（体重/睡眠/负荷、TDEE/目标、滚动 %BW/week、EA、蛋白达成率、肌群组数）
