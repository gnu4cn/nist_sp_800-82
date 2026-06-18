# 系统和通信保护 - SC

## 系统和通信保护系列的定制注意事项

加密技术的使用，是在仔细考虑安全需求和对系统性能的潜在影响后确定的。例如，组织应考虑使用加密技术引起的延迟，是否会对 OT 的操作性能产生不利影响。虽然 OT 中常见的遗留设备通常缺乏对加密功能的直接支持，但可以使用补偿控制（例如封装）来满足控制的意图。

当 OT 无法支持控制的特定系统和通信保护要求时，组织将根据一般定制指南采用补偿控制。每项控制措施都适当地给出了补偿控制的示例。

## SC-1 政策和程序

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-1</b></td>
        <td><b>政策与程序</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：政策专门解决了 OT 的独特属性和要求，以及与非 OT 系统的关系。

## SC-2 系统和用户功能分离

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-2</b></td>
        <td><b>系统和用户功能分离，Separation of System and User Functionality</b></td>
        <td></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：物理分离包括使用单独的系统来管理 OT 和操作 OT 的组件。逻辑分离包括使用不同的用户帐户，来获得管理和操作员权限。补偿控制的示例包括提供更多的审计措施。

## SC-3 安全功能隔离

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-3</b></td>
        <td><b>安全功能隔离，Security Function Isolation</b></td>
        <td></td>
        <td></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：组织在设计新架构或更新现有组件时，应考虑实施此控制措施。补偿控制的示例包括访问控制。

## SC-4 共享系统资源中的信息

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-4</b></td>
        <td><b>共享系统资源中的信息，Information in Shared System Resources</b></td>
        <td></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：这项控制措施对于处理机密数据的 OT 系统尤其相关。示例补偿控制包括设计 OT 的使用，以防止共享系统资源。


## SC-5 拒绝服务保护

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-5</b></td>
        <td><b>拒绝服务的保护</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：由于某些 OT 应用程序的时间紧迫性，OT 设备可能更容易受到 DoS 攻击。基于风险的分析可确定 DoS 保护的优先级，以及政策和程序的制定。

## SC-7 边界保护

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-7</b></td>
        <td><b>边界保护，Boundary Protection</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (3)</td>
        <td><i>边界保护 | 接入点，ACCESS POINTS</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (4)</td>
        <td><i>边界保护 | 对外电信服务</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (5)</td>
        <td><i>边界保护 | 默认拒绝 – 例外允许，DENY BY DEFAULT - ALLOW BY EXECPTION</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (7)</td>
        <td><i>边界保护 | 远程设备的分割隧道</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (8)</td>
        <td><i>边界保护 | 将流量路由到经过身份验证的代理服务器</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (18)</td>
        <td><i>边界保护 | 失效安全</i></td>
        <td></td>
        <td><u><b>添加</b></u></td>
        <td><b>选择</b></td>
    </tr>
    <tr>
        <td>SC-7 (21)</td>
        <td><i>边界保护 | 系统组件的隔离</i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-7 (28)</td>
        <td><i>边界保护 | 到公共网络的连接 </i></td>
        <td><u><b>添加</b></u></td>
        <td><u><b>添加</b></u></td>
        <td><u><b>添加</b></u></td>
    </tr>
    <tr>
        <td>SC-7 (29)</td>
        <td><i>边界保护 | 分离子网以隔离功能</i></td>
        <td><u><b>添加</b></u></td>
        <td><u><b>添加</b></u></td>
        <td><u><b>添加</b></u></td>
    </tr>
</table>

没有针对这一控制措施的 OT 讨论。

<u>控制增强</u>： (3) (4) (5) (7) (8) (21) 没有针对此控制措施的 OT 讨论。

<u>控制增强</u>： (18) <u>OT 讨论</u>：组织应选择适当的故障模式（例如，允许或阻止所有通信）。

<u>控制增强</u>：(28) <u>OT 讨论</u>：组织应考虑每个 OT 系统直接连接到公共网络的必要性，包括潜在的好处、额外的威胁向量，以及与连接引入的公共访问类型特别相关的潜在不利影响。

<u>控制增强</u>： (29) <u>OT 讨论</u>：子网可用于隔离低风险功能与高风险功能，以及控制措施与安全。子网应与其他边界保护技术一起考虑。

<u>将 SC-7 (18) 添加到 MOD 基线的理由</u>：为 OT 物理部分选择故障模式的能力，使 OT 与其他 IT 系统区分开来。这种选择可能对减轻故障的影响产生重大影响。

<u>将 SC-7 (28) 添加到 LOW、MOD 和 HIGH 基线的理由</u>： OT 的使用应仅限于操作所需的个人。从 OT 直接连接到公共网络在 OT 环境中的适用性有限，但潜在风险很大。

<u>将 SC-7 (29) 添加到 LOW、MOD 和 HIGH 基线的理由</u>：在 OT 环境中，子网和分区是隔离功能的常见做法。

## SC-8 传输保密性和完整性

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-8</b></td>
        <td><b>传输的保密性和完整性</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-8 ()</td>
        <td><i>传输的保密性和完整性 | 加密保护</i></td>
        <td></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

<u>控制增强</u>：（1）<u>OT 讨论</u>：在不可信网段传输时，组织应探索所有可能的密码完整性机制（例如数字签名、哈希函数），以保护信息的机密性和完整性。示例补偿控制包括物理保护，例如两个系统组件之间的安全管道（例如，点对点链路）。

## SC-10 网络断开

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-10</b></td>
        <td><b>网络断开</b></td>
        <td></td>
        <td><s>移除</s></td>
        <td><s>移除</s></td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

<u>从 MOD 和 HIGH 基线中删除 SC-10 的理由</u>：OT 系统的 AC-17 (9) ，有效涵盖了此控制措施的目的。

## SC-12 密钥建立和管理

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-12</b></td>
        <td><b>密钥建立和管理</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>SC-12 (1)</td>
        <td><i>密钥建立和管理 | 可用性</i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

## SC-13 加密保护

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-13</b></td>
        <td><b>加密保护</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

## SC-15 协作计算设备

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-15</b></td>
        <td><b>协作计算设备，Collaborative Computing Devices</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

## SC-17 公钥基础设施证书

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-17</b></td>
        <td><b>公钥基础设施证书，Public Key Infrastructure Certificates</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

## SC-18 移动代码

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-18</b></td>
        <td><b>移动代码，Mobile Code</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对此控制措施的 OT 讨论。

## SC-20 安全的名称/地址解析服务（权威来源）

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-20</b></td>
        <td><b>安全的名字/地址解析服务（权威来源）</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：只有在仔细考虑并验证安全名称/地址解析服务不会对 OT 的运行性能产生不利影响之后，才应使用安全名称/地址解析服务。


## SC-21 安全名称/地址解析服务（递归或缓存解析器）

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-21</b></td>
        <td><b>安全的名字/地址解析服务（递归或缓存解析器）</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：只有在仔细考虑并验证安全名称/地址解析服务不会对 OT 的运行性能产生不利影响之后，才应使用安全名称/地址解析服务。

## SC-22 名称/地址解析服务的架构和配置

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-22</b></td>
        <td><b>名字/地址解析服务的架构和配置</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：只有在仔细考虑并验证安全名称/地址解析服务不会对 OT 的运行性能产生不利影响之后，才应使用安全名称/地址解析服务。

## SC-23 会话真实性

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-23</b></td>
        <td><b>会话真实性，Session Authenticity</b></td>
        <td></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：补偿控制的示例包括审计措施。

## SC-24 在已知状态下失败

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-24</b></td>
        <td><b>在已知状态下失败</b></td>
        <td></td>
        <td><u><b>添加</b></u></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：组织应选择适当的故障状态。保存 OT 状态信息，包括 OT 状态变量和 OT 表示的物理状态之间的一致性（例如，阀门是打开还是关闭、通信允许还是阻止、继续操作等）。

<u>将 SC-24 添加到 MOD 基线的理由</u>：作为 OT 架构和设计的一部分，组织应根据 OT 执行的功能和操作环境，选择适当的故障状态。为 OT 物理部分选择故障模式的能力，将 OT 系统与其他 IT 系统区分开来。这种选择可能会对减轻故障的影响产生重大影响，因为他可能会破坏正在进行的物理过程（例如，阀门在关闭位置发生故障，可能会对系统冷却产生不利影响）。

## SC-28 静态信息保护

{{#include ac.md:12:22}}
    <tr>
        <td><b>SC-28</b></td>
        <td><b>静态信息保护，Protection of Information at Rest</b></td>
        <td></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
    <tr>
        <td><b>SC-28 (1)</b></td>
        <td><i>静态信息保护 | 加密保护</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

<u>OT 讨论</u>：只有在仔细考虑和验证不会对 OT 的运行性能产生不利影响后，才能实施加密机制。当加密机制在某些 OT 设备上不可行时，补偿控制可能包括将数据重新定位到支持加密机制的位置。

<u>控制增强</u>： (1) 没有针对此控制措施的 OT 讨论。

## SC-32 系统分区
