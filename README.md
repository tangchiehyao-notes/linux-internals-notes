# linux-internals-notes

## Repo 定位

這個 repository 用來整理從 Firmware Engineer 視角理解 Linux Internals 的長期學習筆記。
內容不會走教科書式寫法，也不會刻意做成教學文章，而是保留之後可以持續補強的理解框架、實務案例、除錯脈絡與面試輸出。

## 整理原則

- 從 Firmware Engineer 視角出發
- 強調理解與因果關係，不靠死背定義
- 每章都預留實務案例、面試題與個人筆記
- 避免放入公司機密、產品細節或內部流程

## 為什麼 Firmware Engineer 需要了解 Linux Internals

- 韌體工作常常會碰到 boot、process、thread、memory、I/O、IPC、system call 與 scheduler 問題。
- 只會呼叫 API 不夠，遇到 hang、crash、latency、resource leak 或效能異常時，需要有系統內部視角。
- Linux internals 也是 Embedded Linux 與 Firmware 面試中很常被拿來驗證深度的主題。

## 這個 Repo 的學習路線

1. 先建立整體系統觀，知道 Linux 是怎麼把硬體、kernel 與 user space 串起來。
2. 再理解執行模型，包含 process、thread、scheduling 與 system call。
3. 接著補上共享資源模型，包含 IPC、synchronization、memory、filesystem 與 I/O。
4. 最後把 networking、debugging 與 interview questions 整理成可反覆複習的輸出。

## 建議閱讀順序

1. [Linux Internals Overview](docs/01-linux-architecture.md)
2. [User Space vs Kernel Space](docs/02-user-space-vs-kernel-space.md)
3. [Process 管理](docs/03-process-management.md)
4. [Thread 與 Scheduling](docs/04-threads-and-scheduling.md)
5. [System Call](docs/05-system-calls.md)
6. [IPC](docs/06-ipc.md)
7. [Synchronization](docs/07-synchronization.md)
8. [記憶體管理](docs/08-memory-management.md)
9. [Filesystem 與 I/O](docs/09-filesystem-and-io.md)
10. [Networking 基礎](docs/10-networking-basics.md)
11. [Linux 除錯](docs/11-linux-debugging.md)
12. [面試題整理](docs/12-interview-questions.md)

## 文件結構

- `docs/`：各章節骨架
- `templates/`：章節模板與面試題模板
- `progress/`：學習進度與複盤 checklist

## 進度追蹤 Checklist

完整版本請看 [progress/learning-checklist.md](progress/learning-checklist.md)。

- [ ] Linux Internals Overview
- [ ] User Space vs Kernel Space
- [ ] Process 管理
- [ ] Thread 與 Scheduling
- [ ] System Call
- [ ] IPC
- [ ] Synchronization
- [ ] 記憶體管理
- [ ] Filesystem 與 I/O
- [ ] Networking 基礎
- [ ] Linux 除錯
- [ ] 面試題整理
- [ ] 完成第一輪閱讀
- [ ] 每章補上一句話總結
- [ ] 每章補上至少 1 個實務案例
- [ ] 每章整理至少 3 題面試題
- [ ] 完成一次整體複盤
