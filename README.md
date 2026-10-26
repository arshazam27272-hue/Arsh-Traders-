// Pure code ko paste karne ke baad bas script section ko is prakar badlein:
function sendToWhatsApp(event) {
    event.preventDefault();
    var name = document.getElementById('buyer-name').value;
    var phone = document.getElementById('buyer-phone').value;
    var req = document.getElementById('buyer-req').value;
    var message = "New B2B Enquiry for Arsh Traders:%0AName: " + name + "%0APhone: " + phone + "%0ARequirement: " + req;
    window.open("https://wa.me" + message, "_blank");
}
