/* 重置与基础样式 */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    min-height: 100vh;
    padding: 20px;
    color: #333;
}

.container {
    max-width: 1400px;
    margin: 0 auto;
    padding: 20px;
}

/* 头部样式 */
.header {
    text-align: center;
    margin-bottom: 30px;
    padding: 20px;
    background: white;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.header h1 {
    color: #2c3e50;
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.header h1 i {
    color: #3498db;
    margin-right: 15px;
}

.subtitle {
    color: #7f8c8d;
    font-size: 1.1rem;
    margin-bottom: 15px;
}

.team-info {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin-top: 15px;
}

.team-name {
    background: #3498db;
    color: white;
    padding: 8px 20px;
    border-radius: 20px;
    font-weight: bold;
}

.task-count {
    background: #2ecc71;
    color: white;
    padding: 8px 20px;
    border-radius: 20px;
    font-weight: bold;
}

/* 添加任务区域 */
.add-task-section {
    background: white;
    padding: 25px;
    border-radius: 15px;
    margin-bottom: 30px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.add-task-section h2 {
    color: #2c3e50;
    margin-bottom: 20px;
    font-size: 1.8rem;
}

.add-task-section h2 i {
    color: #2ecc71;
    margin-right: 10px;
}

.form-group {
    margin-bottom: 20px;
}

input, textarea, select {
    width: 100%;
    padding: 12px 15px;
    border: 2px solid #e0e0e0;
    border-radius: 8px;
    font-size: 1rem;
    transition: border-color 0.3s;
}

input:focus, textarea:focus, select:focus {
    border-color: #3498db;
    outline: none;
}

textarea {
    min-height: 100px;
    resize: vertical;
}

.btn-add {
    background: linear-gradient(135deg, #2ecc71, #27ae60);
    color: white;
    border: none;
    padding: 12px 30px;
    border-radius: 8px;
    font-size: 1.1rem;
    font-weight: bold;
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
    display: flex;
    align-items: center;
    gap: 10px;
    margin: 0 auto;
}

.btn-add:hover {
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(46, 204, 113, 0.4);
}

/* 看板主体 */
.kanban-board {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    margin-bottom: 30px;
}

.column {
    background: white;
    border-radius: 15px;
    padding: 20px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    min-height: 500px;
}

.column-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    padding-bottom: 15px;
    border-bottom: 2px solid #f0f0f0;
}

.column-header h3 {
    font-size: 1.5rem;
    display: flex;
    align-items: center;
    gap: 10px;
}

#todo-column .column-header h3 { color: #e74c3c; }
#doing-column .column-header h3 { color: #f39c12; }
#done-column .column-header h3 { color: #27ae60; }

.column-header .task-count {
    background: #f0f0f0;
    color: #333;
    padding: 5px 15px;
    border-radius: 20px;
    font-weight: bold;
}

/* 任务容器 */
.tasks-container {
    min-height: 400px;
    padding: 10px;
}

/* 任务卡片样式 */
.task-card {
    background: white;
    border-radius: 10px;
    padding: 15px;
    margin-bottom: 15px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.08);
    border-left: 5px solid #3498db;
    transition: transform 0.2s, box-shadow 0.2s;
    cursor: move;
}

.task-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.task-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 10px;
}

.task-title {
    font-size: 1.2rem;
    color: #2c3e50;
    flex: 1;
}

.btn-delete {
    background: #e74c3c;
    color: white;
    border: none;
    width: 30px;
    height: 30px;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.2s;
}

.btn-delete:hover {
    background: #c0392b;
}

.task-desc {
    color: #7f8c8d;
    margin-bottom: 15px;
    line-height: 1.5;
}

.task-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 0.9rem;
}

.task-priority {
    padding: 3px 12px;
    border-radius: 15px;
    font-weight: bold;
    font-size: 0.8rem;
}

.task-priority.low { background: #d5f4e6; color: #27ae60; }
.task-priority.medium { background: #fff3cd; color: #f39c12; }
.task-priority.high { background: #fadbd8; color: #e74c3c; }

.task-date {
    color: #95a5a6;
    font-style: italic;
}

/* 页脚 */
.footer {
    text-align: center;
    padding: 20px;
    color: #7f8c8d;
    font-size: 0.9rem;
    background: white;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}

.hint {
    color: #3498db;
    margin-top: 10px;
    font-weight: bold;
}

/* 响应式设计 */
@media (max-wid
