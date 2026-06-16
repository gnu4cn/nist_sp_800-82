# 物理和环境保护 – PE

## 针对物理和环境保护系列的定制注意事项

物理和环境保护通常用作许多 OT 系统的补偿控制，因此物理和环境保护控制尤为重要。任何选定的补偿控制，都可以将风险降低到可接受的水平。

## PE-1 政策和程序

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-1</b></td>
        <td><b>政策与程序</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：政策专门解决了 OT 的独特属性和要求，以及与非 OT 系统的关系。 OT 组件可以分布在较大的设施占地面积或地理区域内，并且可以是整个组织网络 OT 的入口点。监管控制措施也可能适用。

## PE-2 物理访问授权

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-2</b></td>
        <td><b>物理访问授权</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>


没有针对这项控制措施的 OT 讨论。

## PE-3 物理访问控制

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-3</b></td>
        <td><b>物理访问控制</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
    <tr>
        <td>PE-3 (1)</td>
        <td><i>物理访问控制 | 系统访问</i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>

<u>OT 讨论</u>：组织考虑 OT 安全和安保的相互依赖性，以及紧急情况下的访问要求。在紧急情况下，组织可以限制只有授权人员才能使用 OT 设施和资产。由于时间限制的安全限制，OT 系统通常由不具备，或无法使用全面访问控制功能的设备构成。当电子机制无法满足组织安全计划的安全要求时，组织在必要和可能的情况下，使用物理访问控制和纵深防御措施来补充 OT 安全。

<u>控制增强</u>： (1) 没有针对这一控制措施的 OT 讨论。


## PE-4 传输的访问控制

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-4</b></td>
        <td><b>传输的访问控制</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对这一控制措施的 OT 讨论。

## PE-5 输出设备访问控制

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-5</b></td>
        <td><b>输出设备的访问控制</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>


没有针对这一控制措施的 OT 讨论。

##  PE-6 监控物理访问

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-6</b></td>
        <td><b>监控物理访问</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>PE-6 (1)</td>
        <td><i>监控物理访问 | 入侵警报和监控设备</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>PE-6 (4)</td>
        <td><i>监控物理访问 | 监控对系统的物理访问</i></td>
        <td></td>
        <td><u>添加</u></td>
        <td>选择</td>
    </tr>
</table>


没有针对这一控制措施的 OT 讨论。

<u>控制增强</u>： (1) (4) 没有针对此控制措施的 OT 讨论。

<u>将 PE-6 (4) 添加到 MOD 基线的理由</u>：许多 OT 组件位于偏远的地理位置和分散的位置。其他组件可能位于天花板、地板或配电柜中。此外，当设备缺乏强制逻辑访问限制的能力时，物理访问控制经常被用作补偿控制。

## PE-8 访客访问记录

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-8</b></td>
        <td><b>访客访问记录</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>PE-8 (1)</td>
        <td><i>访客访问记录 | 自动记录维护和审查</i></td>
        <td></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>


没有针对这一控制措施的 OT 讨论。


## PE-9 电力设备和布线

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-9</b></td>
        <td><b>电力设备和布线</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>


没有针对这一控制措施的 OT 讨论。

## PE-10 紧急关闭

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-10</b></td>
        <td><b>紧急关闭</b></td>
        <td></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：关闭某些 OT 的电源，可能是不可能或不明智的。应与安全和操作人员协商实施组织定义的控制参数。示例补偿控制包括失效到已知状态，及紧急程序。

## PE-11 应急电源

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-11</b></td>
        <td><b>应急电源</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>PE-11 (1)</td>
        <td><i>应急电源 | 备用电源 - 最小运行容量, MINIMAL OPERATIONAL CAPACITY</i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
    <tr>
        <td>PE-11 (2)</td>
        <td><i>应急电源 | 备用电源 - 独立式，ALTERNATE POWER SUPPLY - SELF-CONTAINED</i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>


没有针对这一控制措施的 OT 讨论。

## PE-12 应急照明

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-12</b></td>
        <td><b>应急照明</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>


没有针对这一控制措施的 OT 讨论。


## PE-13 消防

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-13</b></td>
        <td><b>消防</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
    <tr>
        <td>PE-13 (1)</td>
        <td><i>消防 | 探测系统 – 自动激活和通知</i></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
    <tr>
        <td>PE-13 (2)</td>
        <td><i>消防 | 抑制系统 – 自动激活和通知</i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>

<u>OT 讨论</u>：灭火机制应考虑 OT 环境（例如，喷水灭火系统在特定环境中可能是危险的）。

<u>控制增强</u>： (1) (2) 没有针对此控制措施的 OT 讨论。

## PE-14 环境控制

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-14</b></td>
        <td><b>环境控制</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
</table>

<u>OT 讨论</u>：温度和湿度控制，通常是其他 OT 系统（例如 HVAC、过程或照明系统）的组件，也可以是独立且独特的 OT 系统。OT 可以在极端环境，以及内部和外部位置运行。对于特定的 OT，温度和湿度设计以及操作参数，决定了性能规格。支持消防和生命安全系统的电源电路、配电柜、路由器和交换机，必须保持在适当的温度和湿度。当无法实施环境控制时，请使用专为承受 OT 独特环境危害而设计的硬件。

## PE-15 水损害保护

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-15</b></td>
        <td><b>水损害保护，Water Damage Protection</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
        <td><b>选择</b></td>
    </tr>
    <tr>
        <td>PE-15 (1)</td>
        <td><i>水灾保护 | </i></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>

<u>OT 讨论</u>：水损害保护以及使用截止阀和隔离阀，属于程序性操作和特定类型的 OT。制造、水电、交通/航海、水和废水处理行业中使用的 OT，依赖于水的运动，专门用于管理水量、流量和压力。支持消防和生命安全系统的电源电路、配电柜、路由器和交换机，应确保水不会使系统瘫痪（例如，启动喷水灭火系统的火灾不会喷洒到消防控制服务器、路由器或交换机上，或使警报器、出口系统、应急照明或灭火系统短路）。

<u>控制增强</u>： (1) 没有针对此控制措施的 OT 讨论。

## PE-16 投放与拆除

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-16</b></td>
        <td><b>投放与拆除, Delivery and Removal</b></td>
        <td>选择</td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对这一控制措施的 OT 讨论。

## PE-17 备用工作地点

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-17</b></td>
        <td><b>备用工作地点</b></td>
        <td></td>
        <td>选择</td>
        <td>选择</td>
    </tr>
</table>

没有针对这一控制措施的 OT 讨论。

## PE-18 系统组件的位置

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-18</b></td>
        <td><b>系统组件的位置</b></td>
        <td></td>
        <td></td>
        <td>选择</td>
    </tr>
</table>

没有针对这一控制措施的 OT 讨论。

## PE-21 电磁脉冲保护

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-21</b></td>
        <td><b>电磁脉冲保护</b></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

<u>OT 讨论</u>：管理 OT 设备的组织可以选择利用 EMP 保护，来防止敌对或环境电磁威胁。组织可以选择遵循国家通信协调中心 National Coordinating Center for Communications, NCC [关于电磁脉冲保护的指南](https://www.cisa.gov/sites/default/files/publications/19_0307_CISA_EMP-Protection-Resilience-Guidelines.pdf)。

## PE-22 组件标记

{{#include ac.md:12:22}}
    <tr>
        <td><b>PE-22</b></td>
        <td><b>组件标记</b></td>
        <td></td>
        <td><u><b>添加</b></u></td>
        <td><u><b>添加</b></u></td>
    </tr>
</table>

<u>OT 讨论</u>：硬件组件被标记或贴上标签，以指示处理、存储或传输的信息。组件标记可用于区分安全和控制系统、OT 和 IT 设备，以及内部和外部连接的系统。标记组件可以降低系统管理不当，或对不正确的设备进行维护的可能性。

<u>将 PE-22 添加到 MOD 和 HIGH 基线的理由</u>：OT 的独特之处在于，他可能看起来像 IT 组件，但执行的功能却截然不同。执行不同功能的组件之间的明显区别，有助于减少由于维护错误而导致的可靠性事故。
