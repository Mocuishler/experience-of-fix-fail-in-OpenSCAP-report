# 一次修复OPENSCP报告中显示问题的经历 (基于PCI-DSS合规性)

### 基础背景:
操作系统: AWS 上的 Amazon Linux 2 (amzn2-ami-hvm-2.0.20210525.0-x86_64.xfs.gpt // 20210603202057)
OpenSCAP : 8 
OpenSCAP command line tool (oscap) 1.2.17
所选规则 : xccdf_org.ssgproject.content_profile_pci-dss
规则版本 : /usr/share/xml/scap/ssg/content/ssg-amzn2-ds.xml ( PCI-DSS v3 Control Baseline )

