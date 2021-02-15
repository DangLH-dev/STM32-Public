# STM32-Public
Những dự án liên quan tới STM32 mà có thể chia sẻ cho cộng đồng

W25QXX SPI FLASH Library for STM32

    Enable SPI and a Gpio as output(CS pin).Connect WP and HOLD to VCC.
    Select General peripheral Initalizion as a pair of '.c/.h' file per peripheral on project settings.
    Config w25qxxConf.h.
    Call W25qxx_Init().
    After init, you can watch w25qxx struct.(Chip ID,page size,sector size and ...)
    In Read/Write Function, you can put 0 to NumByteToRead/NumByteToWrite parameter to maximum.
    Dont forget to erase page/sector/block before write.
