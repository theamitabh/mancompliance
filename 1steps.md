
[cloudshell-user@ip-10-0-135-175 ~]$ aws ec2 describe-instances --output table
-------------------------------------------------------------------------------------
|                                 DescribeInstances                                 |
+-----------------------------------------------------------------------------------+
||                                  Reservations                                   ||
|+---------------------------------+-----------------------------------------------+|
||  OwnerId                        |  5XXXXXXXXX35                                 ||
||  ReservationId                  |  r-0f21447c4f43e18dd                          ||
|+---------------------------------+-----------------------------------------------+|
|||                                   Instances                                   |||
||+------------------------+------------------------------------------------------+||
|||  AmiLaunchIndex        |  0                                                   |||
|||  Architecture          |  x86_64                                              |||
|||  ClientToken           |                                                      |||
|||  EbsOptimized          |  False                                               |||
|||  EnaSupport            |  True                                                |||
|||  Hypervisor            |  xen                                                 |||
|||  ImageId               |  ami-01e78c5619c5e68b4                               |||
|||  InstanceId            |  i-0b71ee4214afa03f0                                 |||
|||  InstanceType          |  t2.micro                                            |||
|||  KeyName               |  development-node-keypair1                           |||
|||  LaunchTime            |  2021-02-07T14:20:41+00:00                           |||
|||  PrivateDnsName        |  ip-172-31-0-137.us-west-2.compute.internal          |||
|||  PrivateIpAddress      |  172.31.0.137                                        |||
|||  PublicDnsName         |  ec2-xxx-xxx-xx-xxx.us-west-2.compute.amazonaws.com  |||
|||  PublicIpAddress       |  xx.xxx.xxx.xxx                                      |||
|||  RootDeviceName        |  /dev/sda1                                           |||
|||  RootDeviceType        |  ebs                                                 |||
|||  SourceDestCheck       |  True                                                |||
|||  StateTransitionReason |                                                      |||
|||  SubnetId              |  subnet-9ee259c3                                     |||
|||  VirtualizationType    |  hvm                                                 |||
|||  VpcId                 |  vpc-d6b7ebae                                        |||
||+------------------------+------------------------------------------------------+||
||||                             BlockDeviceMappings                             ||||
|||+---------------------------------------+-------------------------------------+|||
||||  DeviceName                           |  /dev/sda1                          ||||
|||+---------------------------------------+-------------------------------------+|||
|||||                                    Ebs                                    |||||
||||+--------------------------------+------------------------------------------+||||
|||||  AttachTime                    |  2021-02-07T14:20:42+00:00               |||||
:
