## AWS SYSOPS Notes
* * *

### EBS
##### When restoring a volume from a snapshot, maximum volume performance is not achieved until all blocks on the device have been read. This lesson discusses initializing EBS volumes and when we should use it. (either one can do):
* sudo dd if=/dev/xvdf of=/dev/null bs=1M
* sudo fio --filename=/dev/xvdf --rw=read --bs=128k --iodepth=32 --ioengine=libaio --direct=1 --name=volume-initialize</br>
##### Need to have a backup done before create a read replica for an RDS


* * *
### <center>EC2



* * *
### <center>RDS
#####



* * *
### <center>
 
