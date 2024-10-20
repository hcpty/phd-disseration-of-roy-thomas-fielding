# Readme
A note about Roy Thomas Fielding's PhD dissertation.

### PhD Dissertation of Roy Thomas Fielding

建筑 vs 软件：
- 建筑是由建筑元素组成的，而软件是由软件元素组成的。
- 建筑有建筑结构，而软件有软件结构。
- 建筑中有水、电和燃气等介质的流动，而软件中有数据的流动。

结构 vs 架构：
- 系统一定拥有结构，而只有当一个系统中的元素之间存在物料的输入和输出的时候，才称这个系统拥有架构。
- 为了描述一个系统的架构，不仅要描述这个系统的结构，还要描述这个系统在每一个运行阶段的元素的特点和物料的特点。

菲尔丁发明的Representational State Transfer架构的特点是使用以下6种元素和设计模式：
- Client-Server：Client负责界面交互，Server负责数据存储。
- Stateless (Server)：Client应该存储Client与Server会话的上下文，Server不应该存储Client与Server会话的上下文。
- Cache：Server应该在每个响应中标记当前响应中的数据是否可以被缓存。
- Uniform Interface：
- Layered System：
- Code-On-Demand：

### Credits
- [Architectural Styles and the Design of Network-based Software Architectures](https://ics.uci.edu/~fielding/pubs/dissertation/top.htm)
