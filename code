import qrcode

from pyzbar.pyzbar import decode
from PIL import Image

url = qrcode.make("https://github.com/DhruvMarulkar")
url.save("qrcode.png")

link = decode(Image.open("qrcode.png"))
print(link[0].data.decode())
