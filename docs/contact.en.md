---
title: Contact
--- 

<div class="container-fluid mt-2 mb-5">
    <div class="row">
        <!-- Левая колонка: Контакты -->
        <div class="col-md-6 ps-md-5">
            <h1 style="font-weight: 800; font-size: 2rem; margin-bottom: 10px; color: #222;">contacts</h1>
			
            <p class="mt-1" style="font-style: italic; color: #666; max-width: 400px;">
                Please note that due to profound hearing loss since childhood, I am available for text-based communication only. I accept tasks and messages exclusively in writing. Thank you for your understanding!
            </p>
            <div class="contact-item mb-4">
                <p style="font-size: 1.2rem; color: #888; margin-bottom: 5px;">Ukraine (Viber, WhatsApp):</p>
                <a href="tel:+380637044960" style="font-size: 1.4rem; color: #222; text-decoration: none; font-weight: 500;">+38 063 704 49 60</a>
            </div>

            <div class="contact-item mb-4">
                <p style="font-size: 1.2rem; color: #888; margin-bottom: 5px;">Germany (WhatsApp):</p>
                <a href="tel:+4915126166769" style="font-size: 1.4rem; color: #222; text-decoration: none; font-weight: 500;">+49 151 2616 6769</a>
            </div>

            <div class="contact-item mb-4" style="display: flex; align-items: center; gap: 15px;">
				<p style="font-size: 1.2rem; color: #888; margin: 0;">Telegram:</p>
				<a href="https://t.me/Nenssi7" target="_blank" class="btn btn-outline-info" style="border-radius: 5px; padding: 5px 20px;">@Nenssi7</a>
		    </div>
            
            
        </div>

        <!-- Правая колонка: Контактная форма -->
        <div class="col-md-5 offset-md-1 pe-md-5">
            <div class="card border-0 shadow-sm p-4" style="background: #f8f9fa; border-radius: 10px;">
			    <div class="contact-item mb-4" style="display: flex; align-items: center; gap: 15px;">
				<h3 style="font-weight: 700; margin: 0;">Send a message</h3>

				<div style="flex: 0 0 50px;">
					<img src="../../assets/images/list.jpg" class="img-fluid" style="display: block;">
				</div>
			    </div>    
                
                <!-- Замените your_id на ID от Formspree -->
                <form action="https://formspree.io/f/mqenazrp" method="POST">
                    <div class="mb-3">
                        <label class="form-label">Your Name</label>
                        <input type="text" name="name" class="form-control" placeholder="Your name" required>
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Email</label>
                        <input type="email" name="_replyto" class="form-control" placeholder="name@example.com" required>
                    </div>
                    <div class="mb-3">
                        <label class="form-label">Message</label>
                        <textarea name="message" class="form-control" rows="4" placeholder="How can I help you?" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary w-100" style="background-color: #222; border: none; padding: 10px; font-weight: 600;">Send Message</button>
                </form>
            </div>
        </div>
    </div>
</div>