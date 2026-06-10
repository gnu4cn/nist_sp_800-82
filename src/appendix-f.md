# 附录 F，OT 叠加层

> **读者须知**
>
> OT 叠加层是对 NIST SP 800-53 第 5 版中的控制和控制基线的部分定制，并添加了特定于 OT 的补充指南。叠加层的概念，在 [附录 C](./appendix-c.md#ot-overlay) 的 NIST SP 800-53B 部分进行了讨论。 所谓 OT 叠加层，旨在适用于所有工业部门的所有 OT 系统。进一步的定制可以增加特定部门（例如管道、能源）的特异性。最终，可以为特定系统（例如，XYZ 公司）生成叠加层地图。
>
> 这一 OT 叠加层，构成了 NIST SP 800-53 第 5 版的补充指南和定制。重复的附录 F 的 NIST SP 800-53 部分，会显着增加本出版物的大小，因此此处不包含他。
>
> 创作团队还认为，这一 OT 叠加层可以作为其他叠加层的模型。我们将不胜感激对本附录结构的反馈，特别是在抽象层面，以及补充指南中提供的示例是否足够且有利于实施。


叠加层提供了一种结构化方法，帮助组织定制控制基线并开发可应用于特定任务和业务功能、操作环境和/或技术的专门安全计划。这种专业化方法非常重要，因为目录中威胁驱动的控制措施，以及控制措施增强的数量不断增加，并且组织制定风险管理策略，来在定义的风险承受范围内满足其特定的保护需求。

可以在 [https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/overlay-repository](https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/overlay-repository) 找到叠加层存储库。这一叠加层可以被称为 NIST SP 800-82，修订版 3 《运营技术叠加层》（“NIST SP 800-82 修订版 3 OT 叠加层”）。其基于 NIST SP 800-53，Rev. 5 【[SP800-53r5](./refs.md#sp800-53ar5)】。

NIST 开发这一叠加层，是为了履行 2014 年联邦信息安全现代化法案 the Federal Information Security Modernization Act, FISMA（公法 113-283）【[FISMA](./refs.md#fisma)】、第 21 号总统政策指令 (PPD-21) 【[PPD-21]()】 和 13636 号行政命令 【[EO13636](./refs.md#eo13636)】 规定的法定责任。 NIST 负责制定标准和指南，包括最低要求，为所有机构运营和资产提供足够的信息安全，但未经对此类系统行使政策权力的适当联邦官员的明确批准，此类标准和指南不得适用于国家安全系统。


## 叠加层特性

OT 涵盖与物理环境交互的各种可编程系统和设备（或管理与物理环境交互的设备）。这些系统和设备通过对设备、过程和事件的监视和/或控制，来检测或引起直接变化。示例包括工业控制系统、楼宇自动化系统、交通系统、物理访问控制系统、物理环境监控系统和物理环境测量系统。

ICS 由控制组件（例如电气、机械、液压、气动）组合组成，这些组件共同作用，以实现目标（例如制造、物质或能量的运输）。系统中主要与产生输出有关的部分，称为过程。系统的控制部分包括所需输出或性能的规范。控制可以是完全自动化的，也可以包括人工参与。

[第 2 部分](./program_dev.md) 概述了各种 OT 系统，例如 SCADA、DCS、PLC、BAS、PACS 和 IIoT。

## 适用性

这一叠加层图的目的，是为保护 OT 系统提供指导。这一叠加层已准备好供联邦机构使用。非政府组织可以在自愿的基础上使用他。

隐私属于 OT 系统的一个风险考虑因素。如需更多指导，请参阅 NIST 隐私框架 【[PF](./refs.md#pf)】。隐私在 OT 中的应用将取决于部门和组织风险，因此专门与隐私相关的控制措施，尚未包含在此 OT 叠加层中。每个组织都需要独立确定适用性。根据这一理由，仅出现在隐私基线中的所有控制措施和控制措施增强功能，已从此 OT 叠加层中移除。


## 叠加层摘要

下 [表 22](#t-22) 提供了 NIST SP 800-53 第 5 版，附录 F 【[SP800-53r5](./refs.md#sp800-53r5)】 中，已分配给初始控制基线（即低、中和高）的控制措施及控制措施增强的摘要，以及 OT 讨论和 OT 定制的指示。该表使用以下约定：

- **粗体** 表示通过 OT 讨论进行控制措施和控制措施增强；
- <u>下划线</u> 表示这一叠加层已向基线添加了一项控制措施，该控制措施是对 NIST SP 800-53B 中提供的基线的补充；
- <s>删除线</s> 表示与 NIST SP 800-53B 中提供的基线相比，该基线已删除控制措施或控制措施增强。


在以下示例中，OT 讨论已添加到 AU-4 的控制措施增强 1（粗体）。此外，与不包括 AU-4 控制措施增强 1 的 NIST 800-53B 基线相比，AU-4 的控制措施增强 1 被添加到低、中 (Mod) 和高基线（下划线）中。

<table>
    <tr>
        <td>AU-4</td>
        <td>审计存储容量</td>
        <td>AU-4 <u><b>(1)</b></u></td>
        <td>AU-4 <u><b>(1)</b></u></td>
        <td>AU-4 <u><b>(1)</b></u></td>
    </tr>
</table>

一些控制措施和控制措施增强，对于许多 OT 环境很有用，但并不适用于所有 OT 部门或架构。此类控制措施可能会有额外的 OT 讨论。这些将出现在单独的控制表中。没有基线的控制措施和控制措施增强不包含在下 [表 22](#t-22) 中。


<a name="t-22"></a>
**表 22**：控制措施基线


<table>
    <tr>
        <th rowspan="2">控制措施编号</th>
        <th rowspan="2">控制措施名称</th>
        <th colspan="3">初始控制措施基线</th>
    </tr>
    <tr>
        <th>低 LOW</th>
        <th>中 MOD</th>
        <th>高 HIGH</th>
    </tr>
    <tr>
        <td>AC-1</td>
        <td>政策与程序，Policy and Procedures</td>
        <td><b>AC-1</b></td>
        <td><b>AC-1</b></td>
        <td><b>AC-1</b></td>
    </tr>
    <tr>
        <td>AC-2</td>
        <td>帐号管理</td>
        <td><b>AC-2</b></td>
        <td><b>AC-2</b>(1)<b>(2)</b>(3)(4)<b>(5)(13)</b></td>
        <td><b>AC-2</b>(1)<b>(2)</b>(3)(4)<b>(5)</b>(11)(12)<b>(13)</b></td>
    </tr>
    <tr>
        <td>AC-3</td>
        <td>访问管控，Access Enforcement</td>
        <td><b>AC-3</b></td>
        <td><b>AC-3</b></td>
        <td><b>AC-3 <u>(13)</u></b></td>
    </tr>
    <tr>
        <td>AC-4</td>
        <td>信息流管控，Information Flow Enforcement</td>
        <td></td>
        <td><b>AC-4</b></td>
        <td><b>AC-4</b>(4)</td>
    </tr>
    <tr>
        <td>AC-5</td>
        <td>职责分离，Separation of Duties</td>
        <td></td>
        <td><b>AC-5</b></td>
        <td><b>AC-5</b></td>
    </tr>
    <tr>
        <td>AC-6</td>
        <td>最小权限，Least Privilege</td>
        <td></td>
        <td><b>AC-6 (1)(2)(5)</b>(7)<b>(9)(10)</b></td>
        <td><b>AC-6 (1)(2)(3)(5)</b>(7)<b>(9)(10)</b></td>
    </tr>
    <tr>
        <td>AC-7</td>
        <td>未成功的登录尝试，Unsuccessful Logon Attempts</td>
        <td><b>AC-7</b></td>
        <td><b>AC-7</b></td>
        <td><b>AC-7</b></td>
    </tr>
    <tr>
        <td>AC-8</td>
        <td>系统使用通知，Sytem Use Notification</td>
        <td><b>AC-8</b></td>
        <td><b>AC-8</b></td>
        <td><b>AC-8</b></td>
    </tr>
    <tr>
        <td>AC-10</td>
        <td>并发会话控制，Concurrent Session Control</td>
        <td></td>
        <td></td>
        <td><b>AC-10</b></td>
    </tr>
    <tr>
        <td>AC-11</td>
        <td>设备上锁，Device Lock</td>
        <td></td>
        <td><b>AC-11 (1)</b></td>
        <td><b>AC-11 (1)</b></td>
    </tr>
    <tr>
        <td>AC-12</td>
        <td>会话终止，Session Termination</td>
        <td></td>
        <td><b>AC-12</b></td>
        <td><b>AC-12</b></td>
    </tr>
    <tr>
        <td>AC-14</td>
        <td>无需身份验证或认证的允许行为，Permitted Actions without Identification or Authentication</td>
        <td>AC-14</td>
        <td>AC-14</td>
        <td>AC-14</td>
    </tr>
    <tr>
        <td>AC-17</td>
        <td>远程访问</td>
        <td><b>AC-17 <u>(9)</u></b></td>
        <td><b>AC-17 (1)(2)(3)</b>(4)<b><u>(9)</u></b><u>(10)</u></td>
        <td><b>AC-17 (1)(2)(3)</b>(4)<b><u>(9)</u></b><u>(10)</u></td>
    </tr>
    <tr>
        <td>AC-18</td>
        <td>无线访问</td>
        <td><b>AC-18</b></td>
        <td><b>AC-18 (1)</b>(3)</td>
        <td><b>AC-18 (1)</b>(3)(4)<b>(5)</b></td>
    </tr>
    <tr>
        <td>AC-19</td>
        <td>移动设备的访问控制，Access Control for Mobile Devices</td>
        <td>AC-19</td>
        <td>AC-19 (5)</td>
        <td>AC-19 (5)</td>
    </tr>
    <tr>
        <td>AC-20</td>
        <td>使用外部系统，Use of External System</td>
        <td><b>AC-20</b></td>
        <td><b>AC-20</b>(1)(2)</td>
        <td><b>AC-20</b>(1)(2)</td>
    </tr>
    <tr>
        <td>AC-21</td>
        <td>信息共享</td>
        <td></td>
        <td>AC-21</td>
        <td>AC-21</td>
    </tr>
    <tr>
        <td>AC-22</td>
        <td>公开内容，Publicly Accessible Content</td>
        <td><b>AC-22</b></td>
        <td><b>AC-22</b></td>
        <td><b>AC-22</b></td>
    </tr>
    <tr>
        <td>AT-1</td>
        <td>政策与程序，Policy and Procedures</td>
        <td><b>AT-1</b></td>
        <td><b>AT-1</b></td>
        <td><b>AT-1</b></td>
    </tr>
    <tr>
        <td>AT-2</td>
        <td>扫盲培训和意识，Literacy Training and Awareness</td>
        <td><b>AT-2</b>(2)</td>
        <td><b>AT-2</b>(2)(3)<u><b>(4)</b></u></td>
        <td><b>AT-2</b>(2)(3)<u><b>(4)</b></u></td>
    </tr>
    <tr>
        <td>AT-3</td>
        <td>根据角色的培训，Role-Based Training</td>
        <td><b>AT-3</b></td>
        <td><b>AT-3</b></td>
        <td><b>AT-3</b></td>
    </tr>
    <tr>
        <td>AT-4</td>
        <td>培训记录，Training Records</td>
        <td>AT-4</td>
        <td>AT-4</td>
        <td>AT-4</td>
    </tr>
    <tr>
        <td>AU-1</td>
        <td>政策和程序</td>
        <td><b>AU-1</b></td>
        <td><b>AU-1</b></td>
        <td><b>AU-1</b></td>
    </tr>
    <tr>
        <td>AU-2</td>
        <td>事件日志记录，Event Logging</td>
        <td><b>AU-2</b></td>
        <td><b>AU-2</b></td>
        <td><b>AU-2</b></td>
    </tr>
    <tr>
        <td>AU-3</td>
        <td>审计记录内容，Content of Audit Records</td>
        <td>AU-3</td>
        <td>AU-3</td>
        <td>AU-3</td>
    </tr>
    <tr>
        <td>AU-4</td>
        <td>审计日志存储容量，Audit Log Storage Capacity</td>
        <td>AU-4 <u>(1)</u></td>
        <td>AU-4 <u>(1)</u></td>
        <td>AU-4 <u>(1)</u></td>
    </tr>
    <tr>
        <td>AU-5</td>
        <td>对审计日志记录过程失败的响应, Reponse to Audit Logging Process Failures</td>
        <td>AU-5</td>
        <td>AU-5</td>
        <td>AU-5 (1)(2)</td>
    </tr>
    <tr>
        <td>AU-6</td>
        <td>审计记录回顾、分析与汇报，Audit Record Review, Analysis, and Reporting</td>
        <td>AU-6</td>
        <td>AU-6 <b>(1)</b>(3)</td>
        <td>AU-6 <b>(1)</b>(3)(5)(6)</td>
    </tr>
    <tr>
        <td>AU-7</td>
        <td>审计记录缩减和报告生成，Audit Record Reduction and Report Generation</td>
        <td></td>
        <td>AU-7 (1)</td>
        <td>AU-7 (1)</td>
    </tr>
    <tr>
        <td>AU-8</td>
        <td>时间戳，Time Stamps</td>
        <td><b>AU-8</b></td>
        <td><b>AU-8</b></td>
        <td><b>AU-8</b></td>
    </tr>
    <tr>
        <td>AU-9</td>
        <td>审计信息保护，Protection of Audit Information</td>
        <td>AU-9</td>
        <td>AU-9 (4)</td>
        <td>AU-9 (2)(3)(4)</td>
    </tr>
    <tr>
        <td>AU-10</td>
        <td>不可否认性，Non-repudidation</td>
        <td></td>
        <td></td>
        <td><b>AU-10</b></td>
    </tr>
    <tr>
        <td>AU-11</td>
        <td>审计记录保留, Audit Record Retention</td>
        <td>AU-11</td>
        <td>AU-11</td>
        <td>AU-11</td>
    </tr>
    <tr>
        <td>AU-12</td>
        <td>审计生成, Audit Generation</td>
        <td>AU-12</td>
        <td>AU-12</td>
        <td>AU-12 <b>(1)(3)</b></td>
    </tr>
    <tr>
        <td>CA-1</td>
        <td>政策和程序</td>
        <td><b>CA-1</b></td>
        <td><b>CA-1</b></td>
        <td><b>CA-1</b></td>
    </tr>
    <tr>
        <td>CA-2</td>
        <td>控制措施评估，Control Assessments</td>
        <td><b>CA-2</b></td>
        <td><b>CA-2</b>(1)</td>
        <td><b>CA-2</b>(1)<b>(2)</b></td>
    </tr>
    <tr>
        <td>CA-3</td>
        <td>信息交换，Information Exchange</td>
        <td><b>CA-3</b></td>
        <td><b>CA-3</b></td>
        <td><b>CA-3</b>(6)</td>
    </tr>
    <tr>
        <td>CA-5</td>
        <td>行动计划和里程碑, Plan of Action and Milestones</td>
        <td><b>CA-5</b></td>
        <td><b>CA-5</b></td>
        <td><b>CA-5</b></td>
    </tr>
    <tr>
        <td>CA-6</td>
        <td>授权，Authorization</td>
        <td>CA-6</td>
        <td>CA-6</td>
        <td>CA-6</td>
    </tr>
    <tr>
        <td>CA-7</td>
        <td>持续监控，Continuous Monitoring</td>
        <td><b>CA-7</b>(4)</td>
        <td><b>CA-7</b>(1)(4)</td>
        <td><b>CA-7</b>(1)(4)</td>
    </tr>
    <tr>
        <td>CA-8</td>
        <td>渗透测试，Penetration Testing</td>
        <td></td>
        <td></td>
        <td><b>CA-8</b><s>(1)</s></td>
    </tr>
    <tr>
        <td>CA-9</td>
        <td>内部系统的连接，Internal System Connections</td>
        <td><b>CA-9</b></td>
        <td><b>CA-9</b></td>
        <td><b>CA-9</b></td>
    </tr>
    <tr>
        <td>CM-1</td>
        <td>政策和程序</td>
        <td><b>CM-1</b></td>
        <td><b>CM-1</b></td>
        <td><b>CM-1</b></td>
    </tr>
    <tr>
        <td>CM-2</td>
        <td>基线配置，Baseline Configuration</td>
        <td>CM-2</td>
        <td>CM-2 (2)(3)(7)</td>
        <td>CM-2 (2)(3)(7)</td>
    </tr>
    <tr>
        <td>CM-3</td>
        <td>配置变更控制措施，Configuration Change Control</td>
        <td></td>
        <td><b>CM-3</b>(2)(4)</td>
        <td><b>CM-3</b>(1)(2)(4)(6)</td>
    </tr>
    <tr>
        <td>CM-4</td>
        <td>影响分析，Impact Analysis</td>
        <td><b>CM-4</b></td>
        <td><b>CM-4</b>(2)</td>
        <td><b>CM-4</b>(1)(2)</td>
    </tr>
    <tr>
        <td>CM-5</td>
        <td>变更的访问限制，Access Restrictions for Change</td>
        <td><b>CM-5</b></td>
        <td><b>CM-5</b></td>
        <td><b>CM-5</b>(1)</td>
    </tr>
    <tr>
        <td>CM-6</td>
        <td>配置设置，Configuration Settings</td>
        <td>CM-6</td>
        <td>CM-6</td>
        <td>CM-6 (1)(2)</td>
    </tr>
    <tr>
        <td>CM-7</td>
        <td>最少的功能，Least Functionality</td>
        <td><b>CM-7</b></td>
        <td><b>CM-7</b>(1)(2)<b>(5)</b></td>
        <td><b>CM-7</b>(1)(2)<b>(5)</b></td>
    </tr>
    <tr>
        <td>CM-8</td>
        <td>系统组件库，System Component Inventory</td>
        <td>CM-8</td>
        <td>CM-8 (1)(3)</td>
        <td>CM-8 (1)(2)(3)(4)</td>
    </tr>
    <tr>
        <td>CM-9</td>
        <td>配置管理计划，Configuration Management Plan</td>
        <td></td>
        <td><b>CM-9</b></td>
        <td><b>CM-9</b></td>
    </tr>
    <tr>
        <td>CM-10</td>
        <td>软件使用限制，Software Usage Restrictions</td>
        <td>CM-10</td>
        <td>CM-10</td>
        <td>CM-10</td>
    </tr>
    <tr>
        <td>CM-11</td>
        <td>用户安装的软件，User Installed Software</td>
        <td>CM-11</td>
        <td>CM-11</td>
        <td>CM-11</td>
    </tr>
    <tr>
        <td>CM-12</td>
        <td>信息位置，Information Location</td>
        <td></td>
        <td><b>CM-12</b>(1)</td>
        <td><b>CM-12</b>(1)</td>
    </tr>
    <tr>
        <td>CP-1</td>
        <td>政策与程序</td>
        <td><b>CP-1</b></td>
        <td><b>CP-1</b></td>
        <td><b>CP-1</b></td>
    </tr>
    <tr>
        <td>CP-2</td>
        <td>应急计划，Contingency Plan</td>
        <td><b>CP-2</b></td>
        <td><b>CP-2</b>(1)(3)(8)</td>
        <td><b>CP-2</b>(1)(2)(3)(5)(8)</td>
    </tr>
    <tr>
        <td>CP-3</td>
        <td>应急培训，Contingency Training</td>
        <td>CP-3</td>
        <td>CP-3</td>
        <td>CP-3 (1)</td>
    </tr>
    <tr>
        <td>CP-4</td>
        <td>应急计划测试，Contingency Plan Testing</td>
        <td>CP-4</td>
        <td>CP-4 (1)</td>
        <td>CP-4 (1)<b>(2)</b></td>
    </tr>
    <tr>
        <td>CP-6</td>
        <td>备用存储站点，Alternate Storage Site</td>
        <td></td>
        <td>CP-6 (1)(3)</td>
        <td>CP-6 (1)(2)(3)</td>
    </tr>
    <tr>
        <td>CP-7</td>
        <td>替代处理地点，Alternate Processing Site</td>
        <td></td>
        <td><b>CP-7</b>(1)(2)(3)</td>
        <td><b>CP-7</b>(1)(2)(3)(4)</td>
    </tr>
    <tr>
        <td>CP-8</td>
        <td>电讯服务，Telecommunications Services</td>
        <td></td>
        <td><b>CP-8</b>(1)(2)</td>
        <td><b>CP-8</b>(1)(2))(3)(4)</td>
    </tr>
    <tr>
        <td>CP-9</td>
        <td>系统备份，System Backup</td>
        <td>CP-9</td>
        <td>CP-9<b>(1)</b>(8)</td>
        <td>CP-9<b>(1)(2)</b>(3)(5)(8)</td>
    </tr>
    <tr>
        <td>CP-10</td>
        <td>系统恢复与重建，System Recovery and Reconstitution</td>
        <td><b>CP-10</b></td>
        <td><b>CP-10</b>(2)<u><b>(6)</b></u></td>
        <td><b>CP-10</b>(2)(4)<u><b>(6)</b></u></td>
    </tr>
    <tr>
        <td>CP-12</td>
        <td>安全模式，Safe Mode</td>
        <td><u>CP-12</u></td>
        <td><u>CP-12</u></td>
        <td><u>CP-12</u></td>
    </tr>
    <tr>
        <td>IA-1</td>
        <td>政策与程序</td>
        <td><b>IA-1</b></td>
        <td><b>IA-1</b></td>
        <td><b>IA-1</b></td>
    </tr>
    <tr>
        <td>IA-2</td>
        <td>身份识别和认证（组织用户），Identification and Authentication (Organizational Users)</td>
        <td><b>IA-2(1)(2)</b>(8)<b>(12)</b></td>
        <td><b>IA-2(1)(2)</b>(8)<b>(12)</b></td>
        <td><b>IA-2(1)(2)(5)</b>(8)<b>(12)</b></td>
    </tr>
    <tr>
        <td>IA-3</td>
        <td>设备识别与认证</td>
        <td><u>IA-3</u></td>
        <td>IA-3</td>
        <td>IA-3</td>
    </tr>
    <tr>
        <td>IA-4</td>
        <td>标识符管理，Identifier Management</td>
        <td>IA-4</td>
        <td>IA-4<b>(4)</b></td>
        <td>IA-4<b>(4)</b></td>
    </tr>
    <tr>
        <td>IA-5</td>
        <td>认证器管理, Authenticator Management</td>
        <td><b>IA-5</b>(1)</td>
        <td><b>IA-5</b>(1)(2)(6)</td>
        <td><b>IA-5</b>(1)(2)(6)</td>
    </tr>
    <tr>
        <td>IA-7</td>
        <td>加密模组认证，Cryptographic Module Authentication</td>
        <td>IA-7</td>
        <td>IA-7</td>
        <td>IA-7</td>
    </tr>
    <tr>
        <td>IA-8</td>
        <td>身份识别和认证（非组织用户），Identification and Authentication (Non-Organizational Users)</td>
        <td><b>IA-8(1)(2)(4)</b></td>
        <td><b>IA-8(1)(2)(4)</b></td>
        <td><b>IA-8(1)(2)(4)</b></td>
    </tr>
    <tr>
        <td>IA-11</td>
        <td>重新认证，Re-authentication</td>
        <td>IA-11</td>
        <td>IA-11</td>
        <td>IA-11</td>
    </tr>
    <tr>
        <td>IA-12</td>
        <td>身份证明，Identity Proofing</td>
        <td></td>
        <td><b>IA-12 (2)(3)(5)</b></td>
        <td><b>IA-12 <u>(1)</u>(2)(3)(4)(5)</b></td>
    </tr>
    <tr>
        <td>IR-1</td>
        <td>政策与程序</td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>
    <tr>
        <td>IR-</td>
        <td></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
        <td><b>IR-</b></td>
    </tr>

<table>
