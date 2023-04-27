# Learn Guidelines Support Library

[Guidelines Support Library][gsl] 是 [C++ 核心指南][ccg] 的配套库。

## 目的

提高代码质量，尤其是可读性。

## 必修

[GSL][gsl] 有部分已经被 C++ 20 的 STL 覆盖，比如 gsl::byte。众所周知，现在 C++ 20 是主流……所以本文只划了 4 个重点，其它类可以选修。

- gsl::final_action

- gsl::narrow_cast

- gsl::owner

- gsl::not_null

主要贯彻 [C++ 核心指南][ccg] 提到的以下原则：

- P.1: 在代码中直接表达你的想法

- P.3: 表达你的设计意图

- P.5: 编译期检查优先于运行时检查

- P.8: 不要泄漏任何资源

## 参考

- [【GSL 系列 1】为什么有智能指针还要 gsl::final_action？](https://blog.umu618.com/2022/09/04/umutech-gsl-1-why-final_action/)

- [【GSL 系列 2】为什么需要 gsl::narrow_cast？](https://blog.umu618.com/2022/09/18/umutech-gsl-2-why-narrow_cast/)

- [【GSL 系列 3】为什么需要 gsl::owner？](https://blog.umu618.com/2023/04/22/umutech-gsl-3-why-owner/)

---
[gsl]: https://github.com/microsoft/GSL
[ccg]: https://github.com/UMU618/CppCoreGuidelines-zh-CN