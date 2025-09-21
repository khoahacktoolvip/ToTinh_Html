<!DOCTYPE html><html lang="vi"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tạo nội dung mới</title>
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Dynamic Meta Tags - sẽ được update bằng JavaScript -->
  <meta property="og:title" content="Một câu hỏi cần một người trả lời" id="ogTitle">
  <meta property="og:description" content="Bạn sẽ trả lời thế nào?" id="ogDescription">
  <meta property="og:image" content="images/shocked_1.png" id="ogImage">
  <meta property="og:url" content="https://quickquestionvn.netlify.app/" id="ogUrl">
  <meta property="og:type" content="website">

  <!-- Twitter Card meta tags -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Một câu hỏi cần một người trả lời" id="twitterTitle">
  <meta name="twitter:description" content="Bạn sẽ trả lời thế nào?" id="twitterDescription">
  <meta name="twitter:image" content="https://quickquestionvn.netlify.app/shocked.png" id="twitterImage">
</head>

<body class="bg-gray-100 min-h-screen flex items-center justify-center p-4">
  <!-- Check if this is a shared link -->
  <script>
    // Kiểm tra nếu đây là URL được share
    const path = window.location.pathname;
    const isSharedLink = path.startsWith('/home/');

    if (isSharedLink) {
      // Extract ID from URL
      const id = path.split('/').pop();

      // Update meta tags for better social sharing
      const baseUrl = window.location.origin;
      const shareUrl = `${baseUrl}${path}`;

      // Update Open Graph tags
      document.getElementById('ogTitle').content = `Câu hỏi đặc biệt #${id.substring(0, 8)}`;
      document.getElementById('ogDescription').content = 'Có một câu hỏi dành riêng cho bạn!';
      document.getElementById('ogUrl').content = shareUrl;

      // Update Twitter tags
      document.getElementById('twitterTitle').content = `Câu hỏi đặc biệt #${id.substring(0, 8)}`;
      document.getElementById('twitterDescription').content = 'Có một câu hỏi dành riêng cho bạn!';

      // Update page title
      document.title = `Câu hỏi đặc biệt #${id.substring(0, 8)}`;

      // Load the actual question content
      loadQuestionContent(id);
    }

    function loadQuestionContent(id) {
      // Fetch question data from your API
      fetch(`https://dearlove-backend.onrender.com/api/everything/${id}`)
        .then(res => res.json())
        .then(data => {
          if (data && data.success) {
            // Update meta tags with actual content
            document.getElementById('ogTitle').content = data.data.content || 'Câu hỏi đặc biệt';
            document.getElementById('ogDescription').content = `${data.data.yesText} hoặc ${data.data.noText}?`;
            document.getElementById('twitterTitle').content = data.data.content || 'Câu hỏi đặc biệt';
            document.getElementById('twitterDescription').content = `${data.data.yesText} hoặc ${data.data.noText}?`;

            // Show the question interface
            showQuestionInterface(data.data);
          } else {
            // Redirect to home if question not found
            window.location.href = '/';
          }
        })
        .catch(err => {
          console.error('Error loading question:', err);
          window.location.href = '/';
        });
    }

    function showQuestionInterface(questionData) {
      document.body.innerHTML = `
                <div class="container max-w-md mx-auto mt-20 p-6 bg-white rounded-lg shadow-lg text-center">
                    <img src="/images/heart.png" alt="Trái tim" class="w-20 h-20 mx-auto mb-6">
                    <h1 class="text-2xl font-bold text-gray-800 mb-8">${questionData.content}</h1>
                    <div class="space-y-4">
                        <button onclick="handleAnswer('yes')" class="w-full bg-pink-500 text-white py-3 px-6 rounded-lg hover:bg-pink-600 transition duration-200 text-lg font-medium">
                            ${questionData.yesText}
                        </button>
                        <button onclick="handleAnswer('no')" class="w-full bg-gray-500 text-white py-3 px-6 rounded-lg hover:bg-gray-600 transition duration-200 text-lg font-medium">
                            ${questionData.noText}
                        </button>
                    </div>
                </div>
            `;
    }

    function handleAnswer(answer) {
      if (answer === 'yes') {
        alert('Yay! 🎉');
      } else {
        alert('Aww... 😢');
      }
    }
  </script>

  <div class="w-full max-w-lg bg-white rounded-lg shadow-lg p-6" id="createForm">
    <img src="images/shocked.png" alt="Trái tim" class="w-20 h-20 mx-auto mb-6">
    <h1 class="text-2xl font-bold text-gray-800 mb-6 text-center">Tạo nội dung mới</h1>
    <form id="mainForm" class="space-y-4">
      <div class="form-group">
        <label for="content" class="block text-sm font-medium text-gray-700">Nội dung câu hỏi bạn muốn hỏi:</label>
        <textarea id="content" name="content" rows="4" required="" class="mt-1 block w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-blue-500"></textarea>
      </div>
      <div class="form-group">
        <label for="yesText" class="block text-sm font-medium text-gray-700">Nội dung nút 1:</label>
        <input id="yesText" name="yesText" type="text" required="" class="mt-1 block w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-blue-500" placeholder="Ví dụ: Có">
      </div>
      <div class="form-group">
        <label for="noText" class="block text-sm font-medium text-gray-700">Nội dung nút 2:</label>
        <input id="noText" name="noText" type="text" required="" class="mt-1 block w-full p-3 border border-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:border-blue-500" placeholder="Ví dụ: Không">
      </div>
      <div class="form-group">
        <label class="block text-sm font-medium text-gray-700 mb-1">
          Các câu cho nút "Không" (nhập đủ 5 câu hoặc để trống tất cả).<br>
          <span class="text-xs text-gray-500">
            Nếu bỏ trống, mặc định sẽ hiển thị lần lượt là: <br> Bạn nghiêm túc chứ… <br> Nghĩ lại đi mà?<br>Không được chọn cái này!<br>Mình sẽ buồn lắm đó…<br>Không được đâu :(
          </span>
        </label>
        <div class="grid grid-cols-2 gap-2">
          <input id="noText1" name="noText1" type="text" class="p-3 border border-gray-300 rounded-md" placeholder="Câu 1">
          <input id="noText2" name="noText2" type="text" class="p-3 border border-gray-300 rounded-md" placeholder="Câu 2">
          <input id="noText3" name="noText3" type="text" class="p-3 border border-gray-300 rounded-md" placeholder="Câu 3">
          <input id="noText4" name="noText4" type="text" class="p-3 border border-gray-300 rounded-md" placeholder="Câu 4">
          <input id="noText5" name="noText5" type="text" class="p-3 border border-gray-300 rounded-md col-span-2" placeholder="Câu 5">
        </div>
      </div>
      <button type="submit" id="submitButton" class="w-full bg-blue-600 text-white py-2 px-4 rounded-md hover:bg-blue-700 transition duration-200 flex items-center justify-center disabled:opacity-50">
        <span id="buttonText">Tạo mới</span>
        <svg id="loadingSpinner" class="animate-spin h-5 w-5 ml-2 hidden" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
          <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
          <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z">
          </path>
        </svg>
      </button>
    </form>
    <div id="result" class="mt-4"></div>
  </div>

  <!-- Thêm dialog vào cuối body -->
  <div id="thankYouDialog" class="fixed inset-0 bg-black bg-opacity-40 flex items-center justify-center z-50 hidden">
    <div class="bg-white rounded-lg shadow-lg p-6 max-w-md w-full text-center relative">
      <button onclick="closeDialog()" class="absolute top-2 right-2 text-gray-400 hover:text-gray-700 text-xl">×</button>
      <div id="dialogContent"></div>
    </div>
  </div>

  <script>
    // Only show create form if not a shared link
    if (window.location.pathname.startsWith('/home/')) {
      document.getElementById('createForm').style.display = 'none';
    }

    document.getElementById('mainForm').addEventListener('submit', function (e) {
      e.preventDefault();
      const submitButton = document.getElementById('submitButton');
      const buttonText = document.getElementById('buttonText');
      const loadingSpinner = document.getElementById('loadingSpinner');

      // Show loading state
      submitButton.disabled = true;
      buttonText.textContent = 'Đang tạo...';
      loadingSpinner.classList.remove('hidden');

      const content = document.getElementById('content').value;
      const yesText = document.getElementById('yesText').value;
      const noText = document.getElementById('noText').value;
      const noText1 = document.getElementById('noText1').value.trim();
      const noText2 = document.getElementById('noText2').value.trim();
      const noText3 = document.getElementById('noText3').value.trim();
      const noText4 = document.getElementById('noText4').value.trim();
      const noText5 = document.getElementById('noText5').value.trim();

      const noTextsArr = [noText1, noText2, noText3, noText4, noText5];
      const filledCount = noTextsArr.filter(t => t !== '').length;

      let title = '';
      if (filledCount === 0) {
        title = '';
      } else if (filledCount === 5) {
        title = noTextsArr.join(';');
      } else {
        alert('Bạn phải nhập đủ 5 câu cho nút "Không" hoặc để trống tất cả!');
        submitButton.disabled = false;
        buttonText.textContent = 'Tạo mới';
        loadingSpinner.classList.add('hidden');
        return;
      }

      fetch('https://dearlove-backend.onrender.com/api/everything', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({
          content,
          yesText,
          noText,
          messages: [yesText, noText],
          title
        })
      })
        .then(res => res.json())
        .then(data => {
          console.log('Kết quả trả về:', data);
          if (data && data.data && data.data.id) {
            const link = `home/${data.data.id}`;
            const fullUrl = `${window.location.origin}/${link}`;
            showThankYouDialog(`
        <div class="text-2xl font-bold text-green-700 mb-2">✅ Tạo thành công!</div>
        <div class="bg-green-50 border border-green-200 rounded-lg p-4 mb-2">
          <div class="text-green-800 font-medium mb-2">Cảm ơn bạn đã sử dụng website của mình. <br>
            Nếu bạn thấy nội dung này thú vị, hãy cho mình xin một follow kênh tiktok:
             <a href="https://www.tiktok.com/@iamtritoan?is_from_webapp=1&sender_device=pc" target="_blank" class="text-blue-600 hover:underline">tớ là Toán</a>
              <br>Cảm ơn bạn rất nhiều! ❤️
            </div>
          <div class="text-sm text-gray-600 mb-3">ID: <code class="bg-gray-100 px-2 py-1 rounded">${data.data.id}</code></div>
          <div class="space-y-2">
              <button onclick="copyAndRedirect('${fullUrl}', '${link}')" 
                  class="w-full bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700 transition duration-200">
                  📋 Copy link và xem kết quả
              </button>
              <div id="copyStatus" class="text-green-600 text-sm hidden">✅ Đã copy vào clipboard!</div>
          </div>
        </div>
      `);
          } else {
            showThankYouDialog('<div class="text-red-700 font-bold">❌ Có lỗi xảy ra khi tạo mới!</div>');
          }
        })
        .catch(err => {
          console.error('Lỗi khi gửi request:', err);
          document.getElementById('result').innerHTML =
            '<div class="bg-red-50 border border-red-200 rounded-lg p-4 text-red-800">❌ Không thể kết nối tới máy chủ!</div>';
        })
        .finally(() => {
          // Reset loading state
          submitButton.disabled = false;
          buttonText.textContent = 'Tạo mới';
          loadingSpinner.classList.add('hidden');
        });
    });

    // Global function for copy and redirect
    window.copyAndRedirect = function (fullUrl, link) {
      navigator.clipboard.writeText(fullUrl).then(() => {
        const copyStatus = document.getElementById('copyStatus');
        copyStatus.classList.remove('hidden');
        setTimeout(() => {
          window.location.href = '/' + link;
        }, 1000);
      }).catch(err => {
        console.error('Lỗi khi copy:', err);
        // Fallback: just redirect
        window.location.href = link;
      });
    };

    function showThankYouDialog(html) {
      document.getElementById('dialogContent').innerHTML = html;
      document.getElementById('thankYouDialog').classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }
    function closeDialog() {
      document.getElementById('thankYouDialog').classList.add('hidden');
      document.body.style.overflow = '';
    }
  </script>


</body></html>
