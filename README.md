# esp32_fifo


/* 基于esp32的环形队列 */

Ring queues based on esp32


/* 环形队列应用场景:缓冲区、音频缓冲、视频缓冲、流媒体播放缓冲、TCP/IP数据接收缓冲等 */

Ring queue application scenarios: buffer, audio buffer, video buffer, streaming media play buffer, TCP/IP data receive buffer, etc


Description of ring queue features:

1.Fifo, circular queue                           /* 先进先出，环形队列 */

2.Blocking mechanism, read and write protection  /* 阻塞机制，读写保护 */

3.Fast reading and writing, pointer offset       /* 读写快速，指针偏移 */

4.Interface encapsulation, direct call           /* 接口封装，直接调用 */


Specific use of ring queue:

1.spiRamFifoInit();

2.spiRamFifoReset();

3.spiRamFifoWrite(const char *buff, int buffLen);

4.spiRamFifoRead(char *buff, int len);
