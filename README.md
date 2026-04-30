通讯（Python + FastAPI）

core/event_bus.py— 队列事件，支持发布/订阅、广播、优先级队列
core/base_agent.py— Agent基类，含任务队列、指标采集、生命周期管理
core/agent_manager.py— Agent编排管理器，处理工作流路由与负载均衡
agents/— 6个完整Agent：编排、数据、内容、监控、通知、调度
api/routes.py— REST API + WebSocket 实时主动

前端（可独立运行）

frontend/index.html— 完整的仪表板，不需要遥控器也可直接打开演示文稿

运维

docker-compose.yml+ Dockerfile+nginx.conf
