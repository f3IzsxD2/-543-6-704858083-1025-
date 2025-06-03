<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Phone Number Display</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#4f46e5',
            secondary: '#8b5cf6',
            accent: '#06b6d4'
          }
        }
      }
    }
  </script>
</head>
<body class="bg-gradient-to-br from-gray-900 to-primary min-h-screen flex items-center justify-center p-4">
  <div class="max-w-md w-full">
    <div class="bg-gradient-to-r from-primary/90 to-secondary/80 backdrop-blur-xl rounded-2xl shadow-2xl overflow-hidden transform transition-all duration-700 hover:scale-[1.02]">
      <!-- Decoration Elements -->
      <div class="absolute top-0 left-0 w-full h-1/2 bg-gradient-to-r from-transparent via-accent/10 to-transparent"></div>
      <div class="absolute bottom-0 right-0 w-32 h-32 rounded-full bg-secondary/10"></div>
      <div class="absolute top-10 left-10 w-16 h-16 rounded-full bg-accent/10"></div>
      
      <!-- Main Card Content -->
      <div class="relative z-10 py-8 px-6">
        <div class="text-center">
          <div class="w-16 h-16 bg-gradient-to-br from-accent to-primary rounded-full flex items-center justify-center mx-auto mb-3">
            <i class="fas fa-phone text-white text-2xl transform rotate-12"></i>
          </div>
          
          <h2 class="text-white font-bold text-xl mb-2">My Contact Number</h2>
          <p class="text-gray-300 mb-6">Please feel free to reach out to me</p>
          
          <!-- Number Display -->
          <div class="bg-gray-900/40 backdrop-blur rounded-xl p-6 border-2 border-primary/30 mb-6 transition-all hover:border-accent hover:shadow-lg">
            <div class="text-center">
              <span class="block text-accent text-sm mb-2 tracking-widest font-light">
                <i class="fas fa-key mr-1"></i>Number Verified
              </span>
              <span class="block font-mono text-white text-xl md:text-2xl tracking-[0.2em] font-bold">
                hf token+93704858083
              </span>
            </div>
          </div>
          
          <!-- Call Buttons -->
          <div class="grid grid-cols-2 gap-4 mt-8">
            <button class="py-3 px-4 bg-gradient-to-r from-accent to-primary rounded-xl text-white hover:shadow-lg hover:shadow-accent/30 transition-all flex items-center justify-center">
              <i class="fas fa-comment text-lg mr-2"></i> Message
            </button>
            <button class="py-3 px-4 bg-gradient-to-r from-primary to-secondary rounded-xl text-white hover:shadow-lg hover:shadow-primary/30 transition-all flex items-center justify-center">
              <i class="fas fa-phone-alt text-lg mr-2"></i> Call
            </button>
          </div>
        </div>
        
        <!-- Additional Info -->
        <div class="mt-10 pt-6 border-t border-gray-700/50">
          <div class="text-center text-gray-400 text-sm">
            <p class="mb-2"><i class="fas fa-shield-alt mr-2"></i>Secure Connection</p>
            <p><i class="fas fa-globe-americas mr-2"></i>International Number</p>
          </div>
        </div>
      </div>
    </div>

    <!-- QR Code Scanner -->
    <div class="mt-6 bg-gray-800/20 backdrop-blur rounded-xl p-4 text-center">
      <div class="w-16 h-16 mx-auto bg-gray-800/80 backdrop-blur rounded-lg flex items-center justify-center mb-3">
        <i class="fas fa-qrcode text-accent text-2xl"></i>
      </div>
      <p class="text-white mb-2">Scan for Contact Info</p>
      <p class="text-gray-400 text-sm">Share my contact easily via QR code</p>
    </div>
  </div>

  <!-- Decorative Floating Elements -->
  <div class="absolute bottom-10 right-8 w-6 h-6 rounded-full bg-accent animate-ping opacity-20"></div>
  <div class="absolute top-1/4 left-5 w-3 h-3 rounded-full bg-secondary animate-pulse opacity-70"></div>
  <div class="absolute top-1/3 right-10 w-4 h-4 rounded-full bg-accent animate-bounce opacity-50"></div>
</body>
</html>
