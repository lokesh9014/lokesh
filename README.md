html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato:400,700">
</head>
<body>
    <h1>Contact Manger App </h1>
		<div class="features">
				<div class="features-btn">Read features and manual <span class="badge">important</span></div>
				<ul class="features-list">
					
							</ul>
					</li>
			</ul>
		</div>
    <div class="fields-container">
        <div class="input-field name">
            <label>
                Name:
                <input type="text" placeholder="Given Name...">
            </label>
        </div>
        <div class="input-field family-name">
            <label>
                Family name:
                <input type="text" placeholder="Family Name...">
            </label>
        </div>
        <div class="input-field phone">
            <label>
                Phone:
                <input type="text" placeholder="Phone Num...">
            </label>
        </div>
    </div>
    <button type="button" class="add-cont">Add Contact</button>
		
		<div class="more-option">
			<div class="more-option-btn">More Option</div>
			<div class="option-container">
				<button type="button" class="delete-all">Delete All</button>
				<button type="button" class="save">Save</button>
				<button type="button" class="load">Load</button>
				<div class="delete-one">
					<label>Delete Contact:
						<input type="text" placeholder="Write full name...">
						<span>* Please write full name then delete button to delete specific contact.</span>
					</label>
					<button type="button" class="delete-one-btn">Delete</button>
				</div>
			</div>
		</div>
	
    <div class="contact-indx"></div>
</body>
</html>
