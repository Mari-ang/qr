from PIL import Image
import qrcode

# Paths
qr_url = "https://mari-ang.github.io/qr/"
logo_path = "/mnt/data/A_QR_code_in_the_image_is_black_and_white,_consist.png"
output_path = "/mnt/data/qr_upen_logo.png"

# Create QR code
qr = qrcode.QRCode(error_correction=qrcode.constants.ERROR_CORRECT_H)
qr.add_data(qr_url)
qr.make(fit=True)
qr_img = qr.make_image().convert("RGB")

# Load logo
logo = Image.open(logo_path)

# Resize logo
qr_size = qr_img.size[0]
logo_size = qr_size // 4
logo = logo.resize((logo_size, logo_size))

# Paste logo in center
pos = ((qr_size - logo_size) // 2, (qr_size - logo_size) // 2)
qr_img.paste(logo, pos)

# Save
qr_img.save(output_path)

output_path
