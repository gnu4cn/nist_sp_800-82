# 叠加层摘要

下 [表 22](#t-22) 提供了 NIST SP 800-53 第 5 版，附录 F 【[SP800-53r5](../refs.md#sp800-53r5)】 中，已分配给初始控制基线（即低、中和高）的控制措施及控制措施增强的摘要，以及 OT 讨论和 OT 定制的指示。该表使用以下约定：

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
        <td><b>IR-1</b></td>
        <td><b>IR-1</b></td>
        <td><b>IR-1</b></td>
    </tr>
    <tr>
        <td>IR-2</td>
        <td>事件响应培训，Incident Response Training</td>
        <td>IR-2</td>
        <td>IR-2</td>
        <td>IR-2 (1)(2)</td>
    </tr>
    <tr>
        <td>IR-3</td>
        <td>事件相应测试，Incident Response Testing</td>
        <td></td>
        <td>IR-3 (2)</td>
        <td>IR-3 (2)</td>
    </tr>
    <tr>
        <td>IR-4</td>
        <td>事件处理，Incident Handling</td>
        <td><b>IR-4</b></td>
        <td><b>IR-4</b>(1)</td>
        <td><b>IR-4</b>(1)(4)(11)</td>
    </tr>
    <tr>
        <td>IR-5</td>
        <td>事件监控，Incident Monitoring</td>
        <td>IR-5</td>
        <td>IR-5</td>
        <td>IR-5 (1)</td>
    </tr>
    <tr>
        <td>IR-6</td>
        <td>事件报告，Incident Reporting</td>
        <td><b>IR-6</b></td>
        <td><b>IR-6 (1)</b>(3)</td>
        <td><b>IR-6 (1)</b>(3)</td>
    </tr>
    <tr>
        <td>IR-7</td>
        <td>事件响应援助，Incident Response Assistance</td>
        <td>IR-7</td>
        <td>IR-7 (1)</td>
        <td>IR-7 (1)</td>
    </tr>
    <tr>
        <td>IR-8</td>
        <td>事件响应计划，Incident Response Plan</td>
        <td>IR-8</td>
        <td>IR-8</td>
        <td>IR-8</td>
    </tr>
    <tr>
        <td>MA-1</td>
        <td>政策与程序</td>
        <td>MA-1</td>
        <td>MA-1</td>
        <td>MA-1</td>
    </tr>
    <tr>
        <td>MA-2</td>
        <td>受控的维护，Crontolled Maintenance</td>
        <td>MA-2</td>
        <td>MA-2</td>
        <td>MA-2 (2)</td>
    </tr>
    <tr>
        <td>MA-3</td>
        <td>维护工具，Maintenance Tools</td>
        <td></td>
        <td>MA-3 (1)(2)(3)</td>
        <td>MA-3 (1)(2)(3)</td>
    </tr>
    <tr>
        <td>MA-4</td>
        <td>异地维护，Nonlocal Maintenance</td>
        <td>MA-4</td>
        <td>MA-4 <u>(1)</u></td>
        <td>MA-4 <u>(1)</u><b>(3)</b></td>
    </tr>
    <tr>
        <td>MA-5</td>
        <td>维护人员，Maintenance Personnel</td>
        <td>MA-5</td>
        <td>MA-5</td>
        <td>MA-5 (1)</td>
    </tr>
    <tr>
        <td>MA-6</td>
        <td>定时/及时维护，Timely Maintenance</td>
        <td></td>
        <td>MA-6</td>
        <td>MA-6</td>
    </tr>
    <tr>
        <td>MA-7</td>
        <td>现场维护</td>
        <td><u><b>MA-7</b></u></td>
        <td><u><b>MA-7</b></u></td>
        <td><u><b>MA-7</b></u></td>
    </tr>
    <tr>
        <td>MP-1</td>
        <td>政策与程序</td>
        <td><b>MP-1</b></td>
        <td><b>MP-1</b></td>
        <td><b>MP-1</b></td>
    </tr>
    <tr>
        <td>MP-2</td>
        <td>介质访问，Media Access</td>
        <td>MP-2</td>
        <td>MP-2</td>
        <td>MP-2</td>
    </tr>
    <tr>
        <td>MP-3</td>
        <td>介质标记，Media Access</td>
        <td></td>
        <td>MP-3</td>
        <td>MP-3</td>
    </tr>
    <tr>
        <td>MP-4</td>
        <td>介质存储，Media Storage</td>
        <td></td>
        <td>MP-4</td>
        <td>MP-4</td>
    </tr>
    <tr>
        <td>MP-5</td>
        <td>介质传输，Media Transport</td>
        <td></td>
        <td>MP-5</td>
        <td>MP-5</td>
    </tr>
    <tr>
        <td>MP-6</td>
        <td>介质净化，Media Sanitization</td>
        <td>MP-6</td>
        <td>MP-6</td>
        <td>MP-6 (1)(2)(3)</td>
    </tr>
    <tr>
        <td>MP-7</td>
        <td>介质使用，Meida Use</td>
        <td>MP-7</td>
        <td>MP-7</td>
        <td>MP-7</td>
    </tr>
    <tr>
        <td>PE-1</td>
        <td>政策与程序</td>
        <td><b>PE-1</b></td>
        <td><b>PE-1</b></td>
        <td><b>PE-1</b></td>
    </tr>
    <tr>
        <td>PE-2</td>
        <td>物理访问授权，Physical Access Authorization</td>
        <td>PE-2</td>
        <td>PE-2</td>
        <td>PE-2</td>
    </tr>
    <tr>
        <td>PE-3</td>
        <td>物理访问控制，Physical Access Control</td>
        <td><b>PE-3</b></td>
        <td><b>PE-3</b></td>
        <td><b>PE-3</b>(1)</td>
    </tr>
    <tr>
        <td>PE-4</td>
        <td>传输的访问控制，Access Control for Tansmission</td>
        <td></td>
        <td>PE-4</td>
        <td>PE-4</td>
    </tr>
    <tr>
        <td>PE-5</td>
        <td>输出设备的访问控制，Access Control for Output Devices</td>
        <td></td>
        <td>PE-5</td>
        <td>PE-5</td>
    </tr>
    <tr>
        <td>PE-6</td>
        <td>监控物理访问，Monitoring Physical Access</td>
        <td>PE-6</td>
        <td>PE-6 (1)<u>(4)</u></td>
        <td>PE-6 (1)(4)</td>
    </tr>
    <tr>
        <td>PE-8</td>
        <td>访客访问记录，Visitor Access Records</td>
        <td>PE-8</td>
        <td>PE-8</td>
        <td>PE-8 (1)</td>
    </tr>
    <tr>
        <td>PE-9</td>
        <td>电力设备和布线，Power Equipment and Cabling</td>
        <td></td>
        <td>PE-9</td>
        <td>PE-9</td>
    </tr>
    <tr>
        <td>PE-10</td>
        <td>紧急关闭，Emergency Shutoff</td>
        <td></td>
        <td><b>PE-10</b></td>
        <td><b>PE-10</b></td>
    </tr>
    <tr>
        <td>PE-11</td>
        <td>应急电源，Emergency Power</td>
        <td></td>
        <td>PE-11</td>
        <td>PE-11 (1)</td>
    </tr>
    <tr>
        <td>PE-12</td>
        <td>应急照明，Emergency Lighting</td>
        <td>PE-12</td>
        <td>PE-12</td>
        <td>PE-12</td>
    </tr>
    <tr>
        <td>PE-13</td>
        <td>消防，Fire Protection</td>
        <td><b>PE-13</b></td>
        <td><b>PE-13</b>(1)</td>
        <td><b>PE-13</b>(1)(2)</td>
    </tr>
    <tr>
        <td>PE-14</td>
        <td>环境控制措施，Environmental Controls</td>
        <td><b>PE-14</b></td>
        <td><b>PE-14</b></td>
        <td><b>PE-14</b></td>
    </tr>
    <tr>
        <td>PE-15</td>
        <td>水灾保护，Water Damage Protection</td>
        <td><b>PE-15</b></td>
        <td><b>PE-15</b></td>
        <td><b>PE-15</b>(1)</td>
    </tr>
    <tr>
        <td>PE-16</td>
        <td>运送与搬运，Delivery and Removal</td>
        <td>PE-16</td>
        <td>PE-16</td>
        <td>PE-16</td>
    </tr>
    <tr>
        <td>PE-17</td>
        <td>备用工作地点，Alternate Work Site</td>
        <td></td>
        <td>PE-17</td>
        <td>PE-17</td>
    </tr>
    <tr>
        <td>PE-18</td>
        <td>系统组件的位置，Location of System Components</td>
        <td></td>
        <td></td>
        <td>PE-18</td>
    </tr>
    <tr>
        <td>PE-22</td>
        <td>组件标记，Component Marking</td>
        <td></td>
        <td><u><b>PE-22</b></u></td>
        <td><u><b>PE-22</b></u></td>
    </tr>
    <tr>
        <td>PL-1</td>
        <td>政策与程序</td>
        <td><b>PL-1</b></td>
        <td><b>PL-1</b></td>
        <td><b>PL-1</b></td>
    </tr>
    <tr>
        <td>PL-2</td>
        <td>系统安全和隐私计划，System Security and Privacy Plans</td>
        <td><b>PL-2</b></td>
        <td><b>PL-2</b></td>
        <td><b>PL-2</b></td>
    </tr>
    <tr>
        <td>PL-4</td>
        <td>行为规则，Rules of Behavior</td>
        <td>PL-4 (1)</td>
        <td>PL-4 (1)</td>
        <td>PL-4 (1)</td>
    </tr>
    <tr>
        <td>PL-8</td>
        <td>安全和隐私架构，Security and Privacy Architecture</td>
        <td></td>
        <td>PL-8</td>
        <td>PL-8</td>
    </tr>
    <tr>
        <td>PL-10</td>
        <td>基线选择，Baseline Selection</td>
        <td>PL-10</td>
        <td>PL-10</td>
        <td>PL-10</td>
    </tr>
    <tr>
        <td>PL-11</td>
        <td>基线定制，Baseline Tailoring</td>
        <td>PL-11</td>
        <td>PL-11</td>
        <td>PL-11</td>
    </tr>
    <tr>
        <td>PM-1</td>
        <td>信息安全项目计划，Information Security Program Plan</td>
        <td colspan="3">PM-1</td>
    </tr>
    <tr>
        <td>PM-2</td>
        <td>信息安全计划领导角色，Information Security Program Leadership Role</td>
        <td colspan="3">PM-2</td>
    </tr>
    <tr>
        <td>PM-3</td>
        <td>信息安全与隐私资源，Information Security and Privacy Resources</td>
        <td colspan="3">PM-3</td>
    </tr>
    <tr>
        <td>PM-4</td>
        <td>行动计划和里程碑流程, Plan of Action and Milestones Process</td>
        <td colspan="3">PM-4</td>
    </tr>
    <tr>
        <td>PM-5</td>
        <td>系统库存，System Inventory</td>
        <td colspan="3">PM-5</td>
    </tr>
    <tr>
        <td>PM-6</td>
        <td>性能衡量标准，Measures of Performance</td>
        <td colspan="3">PM-6</td>
    </tr>
    <tr>
        <td>PM-7</td>
        <td>企业架构，Enterprise Architecture</td>
        <td colspan="3">PM-7</td>
    </tr>
    <tr>
        <td>PM-8</td>
        <td>关键基础设施计划，Critical Infrastructure Plan</td>
        <td colspan="3"><b>PM-8</b></td>
    </tr>
    <tr>
        <td>PM-9</td>
        <td>风险管理策略，Risk Management Strategy</td>
        <td colspan="3">PM-9</td>
    </tr>
    <tr>
        <td>PM-10</td>
        <td>授权流程，Authorization Process</td>
        <td colspan="3">PM-10</td>
    </tr>
    <tr>
        <td>PM-11</td>
        <td>使命和业务流程定义，Mission and Business Process Definition</td>
        <td colspan="3">PM-11</td>
    </tr>
    <tr>
        <td>PM-12</td>
        <td>内部威胁计划，Insider Threat Program</td>
        <td colspan="3">PM-12</td>
    </tr>
    <tr>
        <td>PM-13</td>
        <td>安全和隐私工作人员，Security and Privacy Workforce</td>
        <td colspan="3">PM-13</td>
    </tr>
    <tr>
        <td>PM-14</td>
        <td>测试、培训与监控，Testing, Training and Monitoring</td>
        <td colspan="3">PM-14</td>
    </tr>
    <tr>
        <td>PM-15</td>
        <td>安全和隐私团体和协会，Security and Privacy Groups and Associations</td>
        <td colspan="3"><b>PM-15</b></td>
    </tr>
    <tr>
        <td>PM-16</td>
        <td>威胁意识计划，Threat Awareness Program</td>
        <td colspan="3"><b>PM-16</b></td>
    </tr>
    <tr>
        <td>PM-17</td>
        <td>保护外部系统上的受控非机密信息，Protecting Controlled Unclassified Information on External Systems</td>
        <td colspan="3"><b>PM-17</b></td>
    </tr>
    <tr>
        <td>PM-18</td>
        <td>隐私项目计划，Privacy Program Plan</td>
        <td colspan="3">PM-18</td>
    </tr>
    <tr>
        <td>PM-18</td>
        <td>隐私计划领导角色，Privacy Program Leadership Role</td>
        <td colspan="3">PM-19</td>
    </tr>
    <tr>
        <td>PM-20</td>
        <td>隐私计划信息的传播，Dissemination of Privacy Program Information</td>
        <td colspan="3">PM-20 (1)</td>
    </tr>
    <tr>
        <td>PM-21</td>
        <td>披露记录，Accounting of Disclosures</td>
        <td colspan="3">PM-21</td>
    </tr>
    <tr>
        <td>PM-22</td>
        <td>个人身份信息质量管理，Personally Identifiable Information Quality Management</td>
        <td colspan="3">PM-22</td>
    </tr>
    <tr>
        <td>PM-23</td>
        <td>数据治理机构，Data Governance Body</td>
        <td colspan="3">PM-23</td>
    </tr>
    <tr>
        <td>PM-24</td>
        <td>数据完整性委员会，Data Integrity Board</td>
        <td colspan="3">PM-24</td>
    </tr>
    <tr>
        <td>PM-25</td>
        <td>最大限度地减少测试、培训和研究中使用的个人身份信息，Minimization of Personally Identifiable Information Used in Testing, Training, and Research</td>
        <td colspan="3">PM-25</td>
    </tr>
    <tr>
        <td>PM-26</td>
        <td>投诉管理，Compliant Management</td>
        <td colspan="3">PM-26</td>
    </tr>
    <tr>
        <td>PM-27</td>
        <td>隐私报告，Privacy Reporting</td>
        <td colspan="3">PM-27</td>
    </tr>
    <tr>
        <td>PM-28</td>
        <td>搭建风险框架，Risk Framing</td>
        <td colspan="3">PM-28</td>
    </tr>
    <tr>
        <td>PM-29</td>
        <td>风险管理计划领导角色，Risk Management Program Leadership Roles</td>
        <td colspan="3">PM-29</td>
    </tr>
    <tr>
        <td>PM-30</td>
        <td>供应链风险管理策略, Supply Chain Risk Management Strategy</td>
        <td colspan="3">PM-30 (1)</td>
    </tr>
    <tr>
        <td>PM-31</td>
        <td>持续监控策略，Continuous Monitoring Strategy</td>
        <td colspan="3">PM-31</td>
    </tr>
    <tr>
        <td>PM-32</td>
        <td>梳理目标，Purposing</td>
        <td colspan="3">PM-32</td>
    </tr>
    <tr>
        <td>PS-1</td>
        <td>政策与程序</td>
        <td><b>PS-1</b></td>
        <td><b>PS-1</b></td>
        <td><b>PS-1</b></td>
    </tr>
    <tr>
        <td>PS-2</td>
        <td>岗位风险指定，Position Risk Designation</td>
        <td><b>PS-2</b></td>
        <td><b>PS-2</b></td>
        <td><b>PS-2</b></td>
    </tr>
    <tr>
        <td>PS-3</td>
        <td>人员筛选，Personnel Screening</td>
        <td>PS-3</td>
        <td>PS-3</td>
        <td>PS-3</td>
    </tr>
    <tr>
        <td>PS-4</td>
        <td>人员终止，Personnel Termination</td>
        <td>PS-4</td>
        <td>PS-4</td>
        <td>PS-4 (2)</td>
    </tr>
    <tr>
        <td>PS-5</td>
        <td>人员调动，Personnel Transfer</td>
        <td>PS-5</td>
        <td>PS-5</td>
        <td>PS-5</td>
    </tr>
    <tr>
        <td>PS-6</td>
        <td>访问协议，Access Agreements</td>
        <td>PS-6</td>
        <td>PS-6</td>
        <td>PS-6</td>
    </tr>
    <tr>
        <td>PS-7</td>
        <td>外部人员安全，External Personnel Security</td>
        <td>PS-7</td>
        <td>PS-7</td>
        <td>PS-7</td>
    </tr>
    <tr>
        <td>PS-8</td>
        <td>人员制裁，Personnel Sanctions</td>
        <td>PS-8</td>
        <td>PS-8</td>
        <td>PS-8</td>
    </tr>
    <tr>
        <td>PS-9</td>
        <td>岗位描述，Position Descriptions</td>
        <td>PS-9</td>
        <td>PS-9</td>
        <td>PS-9</td>
    </tr>
    <tr>
        <td>RA-1</td>
        <td>政策与程序</td>
        <td><b>RA-1</b></td>
        <td><b>RA-1</b></td>
        <td><b>RA-1</b></td>
    </tr>
    <tr>
        <td>RA-2</td>
        <td>安全分类，Security Categorization</td>
        <td><b>RA-2</b></td>
        <td><b>RA-2</b></td>
        <td><b>RA-2</b></td>
    </tr>
    <tr>
        <td>RA-3</td>
        <td>风险评估，Risk Assessment</td>
        <td>RA-3 (1)</td>
        <td>RA-3 (1)</td>
        <td>RA-3 (1)</td>
    </tr>
    <tr>
        <td>RA-5</td>
        <td>漏洞监控与扫描，Vulnerabillity Monitoring and Scanning</td>
        <td><b>RA-5</b>(2)<b>(11)</b></td>
        <td><b>RA-5</b>(2)(5)<b>(11)</b></td>
        <td><b>RA-5</b>(2)<b>(4)</b>(5)<b>(11)</b></td>
    </tr>
    <tr>
        <td>RA-7</td>
        <td>风险响应，Risk Response</td>
        <td>RA-7</td>
        <td>RA-7</td>
        <td>RA-7</td>
    </tr>
    <tr>
        <td>RA-9</td>
        <td>关键性分析，Criticality Analysis</td>
        <td></td>
        <td>RA-9</td>
        <td>RA-9</td>
    </tr>
    <tr>
        <td>SA-1</td>
        <td>政策与程序</td>
        <td><b>SA-1</b></td>
        <td><b>SA-1</b></td>
        <td><b>SA-1</b></td>
    </tr>
    <tr>
        <td>SA-2</td>
        <td>资源配置，Allocation of Resources</td>
        <td>SA-2</td>
        <td>SA-2</td>
        <td>SA-2</td>
    </tr>
    <tr>
        <td>SA-3</td>
        <td>系统开发发生命周期，System Development Life Cycle</td>
        <td>SA-3</td>
        <td>SA-3</td>
        <td>SA-3</td>
    </tr>
    <tr>
        <td>SA-4</td>
        <td>收购流程，Acquisition Process</td>
        <td><b>SA-4 (10)</b><u>(12)</u></td>
        <td><b>SA-4 (1)(2)(9)(10)</b><u>(12)</u></td>
        <td><b>SA-4 (1)(2)(5)(9)(10)</b><u>(12)</u></td>
    </tr>
    <tr>
        <td>SA-5</td>
        <td>系统文档，System Documentation</td>
        <td>SA-5</td>
        <td>SA-5</td>
        <td>SA-5</td>
    </tr>
    <tr>
        <td>SA-8</td>
        <td>安全与隐私工程原理，Security and Privacy Engineering Principles</td>
        <td>SA-8</td>
        <td>SA-8</td>
        <td>SA-8</td>
    </tr>
    <tr>
        <td>SA-9</td>
        <td>外部系统服务，External System Services</td>
        <td>SA-9</td>
        <td>SA-9 (2)</td>
        <td>SA-9 (2)</td>
    </tr>
    <tr>
        <td>SA-10</td>
        <td>开发者配置管理，Developer Configuration Management</td>
        <td></td>
        <td><b>SA-10</b></td>
        <td><b>SA-10</b></td>
    </tr>
    <tr>
        <td>SA-11</td>
        <td>开发者测试和评估，Developer Testing and Evaluation</td>
        <td></td>
        <td>SA-11</td>
        <td>SA-11</td>
    </tr>
    <tr>
        <td>SA-15</td>
        <td>开发流程、标准和工具, Development Process, Standards, and Tools</td>
        <td></td>
        <td>SA-15 (3)</td>
        <td>SA-15 (3)</td>
    </tr>
    <tr>
        <td>SA-16</td>
        <td>开发者提供的培训，Developer-Provided Training</td>
        <td></td>
        <td></td>
        <td>SA-16</td>
    </tr>
    <tr>
        <td>SA-17</td>
        <td>开发者安全架构和设计，Developer Security Architecture and Design</td>
        <td></td>
        <td></td>
        <td>SA-17</td>
    </tr>
    <tr>
        <td>SA-21</td>
        <td>开发者遴选，Developer Screening</td>
        <td></td>
        <td></td>
        <td>SA-21</td>
    </tr>
    <tr>
        <td>SA-22</td>
        <td>不受支持的系统组建，Unsupported System Components</td>
        <td><b>SA-22</b></td>
        <td><b>SA-22</b></td>
        <td><b>SA-22</b></td>
    </tr>
    <tr>
        <td>SC-1</td>
        <td>政策与程序</td>
        <td><b>SC-1</b></td>
        <td><b>SC-1</b></td>
        <td><b>SC-1</b></td>
    </tr>
    <tr>
        <td>SC-2</td>
        <td>系统和用户功能分离，Separation of System and User Functionality</td>
        <td></td>
        <td><b>SC-2</b></td>
        <td><b>SC-2</b></td>
    </tr>
    <tr>
        <td>SC-3</td>
        <td>安全功能隔离，Security Function Isolation</td>
        <td></td>
        <td></td>
        <td><b>SC-3</b></td>
    </tr>
    <tr>
        <td>SC-4</td>
        <td>系统共享资源中的信息，Information in System Shared Resources</td>
        <td></td>
        <td><b>SC-4</b></td>
        <td><b>SC-4</b></td>
    </tr>
    <tr>
        <td>SC-5</td>
        <td>拒绝服务攻击保护，Denial-of-Service Protection</td>
        <td><b>SC-5</b></td>
        <td><b>SC-5</b></td>
        <td><b>SC-5</b></td>
    </tr>
    <tr>
        <td>SC-7</td>
        <td>边界保护，Boundary Protection</td>
        <td>SC-7 <u><b>(28)(29)</b></u></td>
        <td>SC-7 (3)(4)(5)(7)(8)<u><b>(18)(28)(29)</b></u></td>
        <td>SC-7 (3)(4)(5)(7)(8)<b>(18)</b>(21)<u><b>(28)(29)</b></u></td>
    </tr>
    <tr>
        <td>SC-8</td>
        <td>传输的机密性和完整性，Tansmission Confidentiality and Integrity</td>
        <td></td>
        <td>SC-8 <b>(1)</b></td>
        <td>SC-8 <b>(1)</b></td>
    </tr>
    <tr>
        <td>SC-10</td>
        <td>网络断开，Network Disconnect</td>
        <td></td>
        <td><s>SC-10</s></td>
        <td><s>SC-10</s></td>
    </tr>
    <tr>
        <td>SC-12</td>
        <td>密钥的建立和管理, Cryptographic Key Establishment and Management</td>
        <td>SC-12</td>
        <td>SC-12</td>
        <td>SC-12 (1)</td>
    </tr>
    <tr>
        <td>SC-13</td>
        <td>加密保护，Cryptographic Protection</td>
        <td>SC-13</td>
        <td>SC-13</td>
        <td>SC-13</td>
    </tr>
    <tr>
        <td>SC-15</td>
        <td>协作计算装置与应用，Collaborative Computing Devices and Applications</td>
        <td>SC-15</td>
        <td>SC-15</td>
        <td>SC-15</td>
    </tr>
    <tr>
        <td>SC-17</td>
        <td>公钥基础设施证书，Pulic Key Infrastructure Certificates</td>
        <td></td>
        <td>SC-17</td>
        <td>SC-17</td>
    </tr>
    <tr>
        <td>SC-18</td>
        <td>手机代码，Mobile Code</td>
        <td></td>
        <td>SC-18</td>
        <td>SC-18</td>
    </tr>
    <tr>
        <td>SC-20</td>
        <td>安全名称/地址解析服务（权威来源），Secure Name/Address Resolution Service (Authoritative Source)</td>
        <td><b>SC-20</b></td>
        <td><b>SC-20</b></td>
        <td><b>SC-20</b></td>
    </tr>
    <tr>
        <td>SC-21</td>
        <td>安全名称/地址解析服务（递归或缓存解析器），Secure Name/Address Resolution Service (Recursive or Caching Resolver)</td>
        <td><b>SC-21</b></td>
        <td><b>SC-21</b></td>
        <td><b>SC-21</b></td>
    </tr>
    <tr>
        <td>SC-22</td>
        <td>名称/地址解析服务的架构和配置, Architecture and Provisioning for Name/Address Resolution Service</td>
        <td><b>SC-22</b></td>
        <td><b>SC-22</b></td>
        <td><b>SC-22</b></td>
    </tr>
    <tr>
        <td>SC-23</td>
        <td>会话真实性，Session Authenticity</td>
        <td></td>
        <td><b>SC-23</b></td>
        <td><b>SC-23</b></td>
    </tr>
    <tr>
        <td>SC-24</td>
        <td>已知状态失败，Fail in Known State</td>
        <td></td>
        <td><u><b>SC-24</b></u></td>
        <td><b>SC-24</b></td>
    </tr>
    <tr>
        <td>SC-28</td>
        <td>静态信息保护, Protection of Information at Rest</td>
        <td></td>
        <td><b>SC-28</b>(1)</td>
        <td><b>SC-28</b>(1)</td>
    </tr>
    <tr>
        <td>SC-39</td>
        <td>进程隔离，Process Isolation</td>
        <td><b>SC-39</b></td>
        <td><b>SC-39</b></td>
        <td><b>SC-39</b></td>
    </tr>
    <tr>
        <td>SC-41</td>
        <td>端口和 I/O 设备访问，Port and I/O Device Access</td>
        <td><s>SC-41</s></td>
        <td><s>SC-41</s></td>
        <td><s>SC-41</s></td>
    </tr>
    <tr>
        <td>SC-45</td>
        <td>系统时间同步，System Time Synchronization</td>
        <td><u><b>SC-45</b></u></td>
        <td><u><b>SC-45</b></u></td>
        <td><u><b>SC-45</b></u></td>
    </tr>
    <tr>
        <td>SC-47</td>
        <td>备用通信路径，Alternate Communication Path</td>
        <td></td>
        <td></td>
        <td><u><b>SC-47</b></u></td>
    </tr>
    <tr>
        <td>SI-1</td>
        <td>政策与程序</td>
        <td><b>SI-1</b></td>
        <td><b>SI-1</b></td>
        <td><b>SI-1</b></td>
    </tr>
    <tr>
        <td>SI-2</td>
        <td>缺陷修复, Flaw Remediation</td>
        <td><b>SI-2</b></td>
        <td><b>SI-2</b>(2)</td>
        <td><b>SI-2</b>(2)</td>
    </tr>
    <tr>
        <td>SI-3</td>
        <td>恶意代码防护，Malicious Code Protection</td>
        <td><b>SI-3</b></td>
        <td><b>SI-3</b></td>
        <td><b>SI-3</b></td>
    </tr>
    <tr>
        <td>SI-4</td>
        <td>系统监控，System Monitoring</td>
        <td><b>SI-4</b></td>
        <td><b>SI-4 (2)</b>(4)<b>(5)</b></td>
        <td><b>SI-4 (2)</b>(4)<b>(5)</b>(10)(12)(14)(20)(22)</td>
    </tr>
    <tr>
        <td>SI-5</td>
        <td>安全警报、建议和指令，Security Alerts, Advisories, and Directives</td>
        <td><b>SI-5</b></td>
        <td><b>SI-5</b></td>
        <td><b>SI-5</b>(1)</td>
    </tr>
    <tr>
        <td>SI-6</td>
        <td>安全隐私功能验证，Security and Privacy Function Verification</td>
        <td></td>
        <td></td>
        <td><b>SI-6</b></td>
    </tr>
    <tr>
        <td>SI-7</td>
        <td>软件、固件及信息的完整性，Software, Firmware, and Information Integrity</td>
        <td></td>
        <td><b>SI-7 (1)(7)</b></td>
        <td><b>SI-7 (1)(2)(5)(7)(15)</b></td>
    </tr>
    <tr>
        <td>SI-8</td>
        <td>垃圾邮件防护, Spam Protection</td>
        <td></td>
        <td><b>SI-8</b><s>(2)</s></td>
        <td><b>SI-8</b><s>(2)</s></td>
    </tr>
    <tr>
        <td>SI-10</td>
        <td>信息输入验证, Information Input Validation</td>
        <td></td>
        <td>SI-10</td>
        <td>SI-10</td>
    </tr>
    <tr>
        <td>SI-11</td>
        <td>错误处理, Error Handling</td>
        <td></td>
        <td>SI-11</td>
        <td>SI-11</td>
    </tr>
    <tr>
        <td>SI-12</td>
        <td>信息处理和保留, Information Handling and Retention</td>
        <td>SI-12</td>
        <td>SI-12</td>
        <td>SI-12</td>
    </tr>
    <tr>
        <td>SI-13</td>
        <td>可预测的故障预防, Predictable Failure Prevention</td>
        <td></td>
        <td></td>
        <td><u>SI-13</u></td>
    </tr>
    <tr>
        <td>SI-16</td>
        <td>存储体保护，Memory Protection</td>
        <td></td>
        <td>SI-16</td>
        <td>SI-16</td>
    </tr>
    <tr>
        <td>SI-17</td>
        <td>故障安全程序，Fail-Safe Procedures</td>
        <td><u><b>SI-17</b></u></td>
        <td><u><b>SI-17</b></u></td>
        <td><u><b>SI-17</b></u></td>
    </tr>
    <tr>
        <td>SR-1</td>
        <td>政策与程序</td>
        <td><b>SR-1</b></td>
        <td><b>SR-1</b></td>
        <td><b>SR-1</b></td>
    </tr>
    <tr>
        <td>SR-2</td>
        <td>供应链风险管理计划，Supply Chain Risk Management Plan</td>
        <td>SR-2 (1)</td>
        <td>SR-2 (1)</td>
        <td>SR-2 (1)</td>
    </tr>
    <tr>
        <td>SR-3</td>
        <td>供应链控制措施和流程，Suplly Chain Controls and Processes</td>
        <td>SR-3</td>
        <td>SR-3</td>
        <td>SR-3</td>
    </tr>
    <tr>
        <td>SR-5</td>
        <td>采购策略、工具及方法，Acquisition Strategies, Tools, and Methods</td>
        <td>SR-5</td>
        <td>SR-5 <u><b>(1)</b></u></td>
        <td>SR-5 <u><b>(1)</b></u></td>
    </tr>
    <tr>
        <td>SR-6</td>
        <td>供应商评估和审查，Supplier Assessments and Reviews</td>
        <td></td>
        <td>SR-6</td>
        <td>SR-6</td>
    </tr>
    <tr>
        <td>SR-8</td>
        <td>通知协议，Notification Agreements</td>
        <td>SR-8</td>
        <td>SR-8</td>
        <td>SR-8</td>
    </tr>
    <tr>
        <td>SR-9</td>
        <td>防篡改和检测, Tamper Resistance and Detection</td>
        <td></td>
        <td></td>
        <td>SR-9 (1)</td>
    </tr>
    <tr>
        <td>SR-10</td>
        <td>系统或组件的检查，Inspection of Systems or Components</td>
        <td>SR-10</td>
        <td>SR-10</td>
        <td>SR-10</td>
    </tr>
    <tr>
        <td>SR-11</td>
        <td>组件真实性，Component Authenticity</td>
        <td>SR-11 (1)(2)</td>
        <td>SR-11 (1)(2)</td>
        <td>SR-11 (1)(2)</td>
    </tr>
    <tr>
        <td>SR-12</td>
        <td>组件处置, Component Disposal</td>
        <td>SR-12</td>
        <td>SR-12</td>
        <td>SR-12</td>
    </tr>
<table>
