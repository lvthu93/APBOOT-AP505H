The 0x100000 and 0x200000 on each units are similar 100% so just need one for compare

AP22D (APBoot_2.6.7.0)

tuxedo@TAPHOA-PC:~$ binwalk -Me AP22D.bin

                                                    /home/tuxedo/extractions/AP22D.bin
----------------------------------------------------------------------------------------------------------------------------------------
DECIMAL                            HEXADECIMAL                        DESCRIPTION
----------------------------------------------------------------------------------------------------------------------------------------
188976                             0x2E230                            CRC32 polynomial table, little endian
320048                             0x4E230                            CRC32 polynomial table, little endian
451120                             0x6E230                            CRC32 polynomial table, little endian
582192                             0x8E230                            CRC32 polynomial table, little endian
713264                             0xAE230                            CRC32 polynomial table, little endian
844336                             0xCE230                            CRC32 polynomial table, little endian
975408                             0xEE230                            CRC32 polynomial table, little endian
1048576                            0x100000                           uImage firmware image, header size: 64 bytes, data size: 315287
                                                                      bytes, compression: lzma, CPU: ARM, OS: Firmware, image type:
                                                                      Firmware Image, load address: 0x1000000, entry point: 0x0,
                                                                      creation time: 2023-05-19 16:37:54, image name: "APBoot 2.6.7.0"
2097152                            0x200000                           uImage firmware image, header size: 64 bytes, data size: 315287
                                                                      bytes, compression: lzma, CPU: ARM, OS: Firmware, image type:
                                                                      Firmware Image, load address: 0x1000000, entry point: 0x0,
                                                                      creation time: 2023-05-19 16:37:54, image name: "APBoot 2.6.7.0"
----------------------------------------------------------------------------------------------------------------------------------------
[+] Extraction of uimage data at offset 0x100000 completed successfully
[+] Extraction of uimage data at offset 0x200000 completed successfully
----------------------------------------------------------------------------------------------------------------------------------------


                                  /home/tuxedo/extractions/AP22D.bin.extracted/200000/APBoot_2.6.7.0.bin
----------------------------------------------------------------------------------------------------------------------------------------
DECIMAL                            HEXADECIMAL                        DESCRIPTION
----------------------------------------------------------------------------------------------------------------------------------------
0                                  0x0                                LZMA compressed data, properties: 0x5D, dictionary size: 8388608
                                                                      bytes, compressed size: 315287 bytes, uncompressed size: 793872
                                                                      bytes
----------------------------------------------------------------------------------------------------------------------------------------
[+] Extraction of lzma data at offset 0x0 completed successfully
----------------------------------------------------------------------------------------------------------------------------------------


                                  /home/tuxedo/extractions/AP22D.bin.extracted/100000/APBoot_2.6.7.0.bin
----------------------------------------------------------------------------------------------------------------------------------------
DECIMAL                            HEXADECIMAL                        DESCRIPTION
----------------------------------------------------------------------------------------------------------------------------------------
0                                  0x0                                LZMA compressed data, properties: 0x5D, dictionary size: 8388608
                                                                      bytes, compressed size: 315287 bytes, uncompressed size: 793872
                                                                      bytes
----------------------------------------------------------------------------------------------------------------------------------------
[+] Extraction of lzma data at offset 0x0 completed successfully
----------------------------------------------------------------------------------------------------------------------------------------



AP505H (APBoot_2.5.3.7)

tuxedo@TAPHOA-PC:~$ binwalk -Me AP505H.bin

                                                    /home/tuxedo/extractions/AP505H.bin
----------------------------------------------------------------------------------------------------------------------------------------
DECIMAL                            HEXADECIMAL                        DESCRIPTION
----------------------------------------------------------------------------------------------------------------------------------------
188976                             0x2E230                            CRC32 polynomial table, little endian
320048                             0x4E230                            CRC32 polynomial table, little endian
451120                             0x6E230                            CRC32 polynomial table, little endian
582192                             0x8E230                            CRC32 polynomial table, little endian
713264                             0xAE230                            CRC32 polynomial table, little endian
844336                             0xCE230                            CRC32 polynomial table, little endian
975408                             0xEE230                            CRC32 polynomial table, little endian
1048576                            0x100000                           uImage firmware image, header size: 64 bytes, data size: 314731
                                                                      bytes, compression: lzma, CPU: ARM, OS: Firmware, image type:
                                                                      Firmware Image, load address: 0x1000000, entry point: 0x0,
                                                                      creation time: 2020-02-19 04:21:34, image name: "APBoot 2.5.3.7"
2097152                            0x200000                           uImage firmware image, header size: 64 bytes, data size: 314731
                                                                      bytes, compression: lzma, CPU: ARM, OS: Firmware, image type:
                                                                      Firmware Image, load address: 0x1000000, entry point: 0x0,
                                                                      creation time: 2020-02-19 04:21:34, image name: "APBoot 2.5.3.7"
----------------------------------------------------------------------------------------------------------------------------------------
[+] Extraction of uimage data at offset 0x100000 completed successfully
[+] Extraction of uimage data at offset 0x200000 completed successfully
----------------------------------------------------------------------------------------------------------------------------------------


                                  /home/tuxedo/extractions/AP505H.bin.extracted/200000/APBoot_2.5.3.7.bin
----------------------------------------------------------------------------------------------------------------------------------------
DECIMAL                            HEXADECIMAL                        DESCRIPTION
----------------------------------------------------------------------------------------------------------------------------------------
0                                  0x0                                LZMA compressed data, properties: 0x5D, dictionary size: 8388608
                                                                      bytes, compressed size: 314731 bytes, uncompressed size: 792356
                                                                      bytes
----------------------------------------------------------------------------------------------------------------------------------------
[+] Extraction of lzma data at offset 0x0 completed successfully
----------------------------------------------------------------------------------------------------------------------------------------


                                  /home/tuxedo/extractions/AP505H.bin.extracted/100000/APBoot_2.5.3.7.bin
----------------------------------------------------------------------------------------------------------------------------------------
DECIMAL                            HEXADECIMAL                        DESCRIPTION
----------------------------------------------------------------------------------------------------------------------------------------
0                                  0x0                                LZMA compressed data, properties: 0x5D, dictionary size: 8388608
                                                                      bytes, compressed size: 314731 bytes, uncompressed size: 792356
                                                                      bytes
----------------------------------------------------------------------------------------------------------------------------------------
[+] Extraction of lzma data at offset 0x0 completed successfully
----------------------------------------------------------------------------------------------------------------------------------------
