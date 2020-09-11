# Project 1 - Netflix EDA

Data visualization in R for Netflix Database 2019

In this project I have analysed the Netflix database from Kaggle using R. 
The database comprises of data about TV shows and movie content on Netflix.

data:image/png;base64,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%0AHpGWU38LMU6SRZkm0ppQ38a+eXz47Xral8VWeQ8IkSAqkdaErf5RURdEgqj8lRXsryzniySL%0AMs1fWcH+ynK+SLIo0/yVFeyvLOeLJIsS43Y+7ZpnIO0Og6cNPU/V07cPj+f9WP3N8Ckil/qR%0AL9t9+43Pg4M6PxW9ll/Pbdkde8/SHnlw3JJTAmMFPUeenrTwtmavZ6w0zzs5vR7t7pxn8HK+%0ALh1LN6uIYZHuvSfDle+ntL1/fnfGp1faUz/alze/D6Z6/6b7U9F99/q9pHNotzn2yMzy6clE%0AQe0qviyIqfO0tUP1MMLvdZqpeQYu52PioV8x44uNYZGGub+2XyP98Xr/O3FvK//Zxr9/0f2p%0AJ9JEm0FrwlRB43P1T6n/TMj21JPzDFvOU++ds0yzuhgWaXCl/90tYw+SbPisKYfBW69to9eu%0AXYfWdfiAfZPJgsbmumDXbvTJyLPzDFrOSM0qY1ikKvft/nRtnqx4q/vvvfH7rG+nzqt3rzW/%0A3bweJ98Y+X0cc2tdG/7YdPD+cv/Ms/dkx97UfrgLWt3sa6U+XKvdq/vlvYr7zHP1ch5ezd5a%0AzV46U8nH9wOSLCoO1bX/9kPhm8GP3VfNu/Xzlb97HM9z2enRWZF2n93+U9Hbz1+3JswUtLbZ%0A5gHrra36/X20Pz/PtctZj8AoTt2fy84xqHh8vyDJoiLR6oPq5X3kVfPu7iPXi3oF2420M/xx%0A+GZvzNuaNWGmoLXN1nu/nVMsl69Ii0PwW86y+wn0muVhYiqZ+H5BkkVFoifS5Kt6W9x7oH17%0Aa7xQpF7EK9aEuYJWNluvw2X3e0sfWYJCmC6o/gA6D3/1GJ9KJL6fkGRRgjzO++b07qa5oPT6%0AtVOkatd832tn19ps/lykuYJWNlu32z3Sel42r129oBCmC9r3P0lfzb739RApSTrXSIpWHzhF%0A2g62xc3WeDuYeOTHGGvCXEErm63bvTneWx3CdEHlyCxvLbkQKUV6V2R9RRrtq9GJR36MsSbM%0AFbSyWec0QSFMNz7skYZyfCpESoGxaySvtxBpbpofixTYrD5JFiVD41FzSeJ5v52PviJVux/9%0AW4c8fLeaMdaEuYJWNuucJiiE6cYnr4WHNatPkkWJUJ8M2vXHpA1ejrxqH/y+aV+u/blIcwWt%0AbHb0OMh3niuXc3DQikipU60l3Yt5viJVCvZuVVNfQzkP2xn+GGNNmCtoZbOjZ+b+zawe/h0U%0A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%0AC0RSApFsgUhKIJItEEmJOZF2xesvTptic3K9HECXKoBISsyIdCleIh2KisP0yyF0qQKIpIRb%0ApMqj+i/uRbF/7oviPvVyBLpUAURSwiXSfVe8RToWxe15K4rj1MsR6FIFEEkJl0j/JNq+RGoO%0AlYpiN/VyBLpUAURSwi3S7vkSqXwpU069HIEuVQCRlHCJtL083yIVL2WKqZft9l7/gru04J/z%0An3zo/+kvVOr/pnC9V7+/UKQWwSLBcoJFgnUgki0QSYmFIpVTL0egSxVAJCU8ReKsXSYgkhKe%0AInEdKRMQSQlPkW7fMQzjL0egSxVAJCU8Rap0eY+qG385hC5VAJGU8BXpeSw/47zHXw6gSxVA%0AJCXmRAqALlUAkZRAJFsgkhKIZAtEUgKRbIFISiCSLRBJCUSyBSIpgUi2QCQlEMkWiKQEItkC%0AkZRAJFsgkhKIZAtEUgKRbIFISiCSLRBJCUSyBSIpgUi2QCQlEMkWiKQEItkCkZRAJFsgkhKI%0AZAtEUgKRbIFISqQuEivGMmTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUg%0Aki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0%0AxSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTy%0AIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJIt%0AZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUg%0Aki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xSCSLWTyIvTFIJItZPIi9MUgki1k8iL0%0AxSCSLWTyIvTFIJItZPIi9MUgki1k8iL0xfwNkWRayYEU8hItJRcQyb+VHEghL9FScgGR/FvJ%0AgRTyEi0lFxDJv5UcSCEv0VJyAZH8W8mBFPISLSUXEMm/lRxIIS/RUnIBkfxbyYEU8hItJRcQ%0Ayb+VHEghL9FScgGR/FvJgRTyEi0lFxDJv5UcSCEv0VJyAZH8W8mBFPISLSUXEMm/lRxIIS/R%0AUnIBkfxbyYEU8hItJRcQyb+VHEghL9FScgGR/FvJgRTyEi0lFxDJv5UcSCEv0VJyAZH8W8mB%0A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
