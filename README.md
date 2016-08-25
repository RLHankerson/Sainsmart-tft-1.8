# Sainsmart-tft-1.8
Need your help!!! My sainsmart tft 1.8 is no longer responsive to my Arduino UNO.   
Listed below is the following code, but my board doesn't seem be be communicating with my sainsmart because it doesn't run the code.
#define SCLK 13
#define MOSI 11
#define CS   10
#define DC   9
#define RES  8  


#include <Adafruit_ST7735.h> // Hardware-specific library
#include <Adafruit_GFX.h> // Core graphics library
#include <SPI.h>
#include <SD.h>

Adafruit_ST7735 tft = Adafruit_ST7735(CS, MOSI, SCLK, DC, RES);
