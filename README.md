// contents of file: ~/some/path/data/login.json
    [
      {"url":"/api/something".
       "response": [{name: caspian},{name: superman}],
       "code": 200,
       "cookie": {
         "name":"my cookie",
         "value":"somevalue",
         "path":"/"
       } 
      }
    ].header {
  background: white;
  height: 44px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.back-arrow {
  position: absolute;
  left: 12px;
  width: 24px;
  height: 24px;
  background: url('data:image/svg+xml;utf8,<svg width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M15 18l-6-6 6-6" stroke="%23000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>') center/contain no-repeat;
}

.header-title {
  font-size: 17px;
  font-weight: 600;
}

.tab-wrapper {
  background: #E5E5EA;
  margin: 10px 16px;
  border-radius: 10px;
  display: flex;
  padding: 4px;
}

.tab {
  flex: 1;
  text-align: center;
  padding: 8px 0;
  font-size: 15px;
  font-weight: 500;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s;
  color: #1C1C1E;
}

.tab.active {
  background: #ffffff;
}

.content-container {
  overflow: hidden;
  position: relative;
  width: 100%;
}

.tab-content {
  display: flex;
  width: 200%;
  transition: transform 0.3s ease;
}

.tab-pane {
  width: 100%;
  padding: 16px;
  box-sizing: border-box;
}

.card {
  position: relative;
  width: 350px;
  margin: 0 auto;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.05);
  overflow: hidden;
}

.card img.bg {
  width: 100%;
  display: block;
}

.photo-area {
  position: absolute;
  top: 58px;
  left: 20px;
  width: 100px;
  height: 120px;
  background: #e5e5ea;
  border-radius: 6px;
  overflow: hidden;
}

.photo-area input {
  width: 100%;
  height: 100%;
  opacity: 0;
  cursor: pointer;
}

.photo-area img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.form {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
  padding: 16px;
  width: 350px;
  margin: 0 auto;
}

.field {
  margin-bottom: 12px;
}

.field label {
  display: block;
  font-size: 13px;
  color: #6e6e73;
  margin-bottom: 4px;
}

.field input {
  width: 100%;
  padding: 10px;
  border: 1px solid #c7c7cc;
  border-radius: 6px;
  font-size: 15px;
}

.buttons {
  padding: 20px;
}

.btn {
  width: 100%;
  padding: 14px;
  font-size: 17px;
  font-weight: 600;
  border-radius: 10px;
  border: none;
  cursor: pointer;
  margin-bottom: 12px;
}

.btn.present {
  background: #5A8DFF;
  color: white;
}

.btn.send {
  background: white;
  color: #5A8DFF;
  border: 1px solid #5A8DFF;
}<!-- Реквизиты -->
  <div class="tab-pane">
    <div class="form">
      <div class="field"><label>ФИО</label><input type="text" placeholder="Иванов Иван Иванович"></div>
      <div class="field"><label>ИИН</label><input type="text" placeholder="123456789012"></div>
      <div class="field"><label>Дата рождения</label><input type="date"></div>
      <div class="field"><label>Номер документа</label><input type="text" placeholder="N12345678"></div>
      <div class="field"><label>Дата выдачи</label><input type="date"></div>
      <div class="field"><label>Срок действия</label><input type="date"></div>
    </div>
  </div>
</div>
