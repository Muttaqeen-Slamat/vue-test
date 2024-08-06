<template>
    <div class="video-container">
      <video
        class="background-video"
        autoplay
        muted
        loop
        playsinline
        src="https://lcstudio.co.za/wp-content/uploads/2023/09/L-4.mp4"
      ></video>
      <div class="content-container">
        <div class="d-flex align-items-center py-4 bg-body-tertiary" data-new-gr-c-s-check-loaded="14.1190.0" data-gr-ext-installed="">
          <main class="form-signin w-100 m-auto">
            <form>
              <h1 class="h3 mb-3 fw-normal">Please sign in</h1>
              <div class="form-floating">
                <input
                  type="email"
                  class="form-control"
                  id="floatingInput"
                  placeholder="name@example.com"
                  fdprocessedid="dv61z"
                />
                <label for="floatingInput">Email address</label>
              </div>
              <div class="form-floating">
                <input
                  type="password"
                  class="form-control"
                  id="floatingPassword"
                  placeholder="Password"
                  fdprocessedid="mtase"
                />
                <label for="floatingPassword">Password</label>
              </div>
              <div class="form-check text-start my-3">
                <input
                  class="form-check-input"
                  type="checkbox"
                  value="remember-me"
                  id="flexCheckDefault"
                />
                <label class="form-check-label" for="flexCheckDefault">
                  Remember me
                </label>
              </div>
              <button
                class="btn btn-primary py-2"
                type="submit"
                fdprocessedid="kp6fak"
              >
                Sign in
              </button>
              <p class="mt-5 mb-3 text-body-secondary">LC Studio</p>
            </form>
          </main>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  .video-container {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }
  
  .background-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: -1;
  }
  
  .content-container {
    position: relative;
    z-index: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  
  .form-signin {
    background: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  </style>
  