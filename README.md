## <center>AWS SYSOPS Notes
* * *
### <center>EBS
##### When restoring a volume from a snapshot, maximum volume performance is not achieved until all blocks on the device have been read. This lesson discusses initializing EBS volumes and when we should use it. (either one can do):
- <code> sudo dd if=/dev/xvdf of=/dev/null bs=1M
- <code> sudo fio --filename=/dev/xvdf --rw=read --bs=128k --iodepth=32 --ioengine=libaio --direct=1 --name=volume-initialize



* * *
### <center>EC2



* * *
### <center>RDS
#####



* * *
### <center>
