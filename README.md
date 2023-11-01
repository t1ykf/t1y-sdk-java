T1 后端云 java SDK 开发文档

本文档是 T1 后端云 官方提供的 Java SDK，方便 Java 开发人员快速使用 T1 进行后端开发。

# 准备工作

## 环境
 jdk：8+
 
## SDK 导入

```gradle
 dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://www.jitpack.io' }
		}
	}

  dependencies {
		implementation '等待更新'
	}
 
```

## 类库说明

- 初始化 SDK

```java
// 初始化 SDK 配置
 T1Cloud t1y= T1Cloud.Init("您的域名", 您的Application ID, "您的API Key", "您的Secret Key")
```

- 创建一条数据

```java

```

- 删除一条数据

```java

```

- 更新一条数据

```java

```

- 查询一条数据

```java

```

- 查询全部数据（分页查询）

```java

```

## 运行效果

打开项目中的 `examples/main.java` 文件，可以看到如何使用 java SDK 相关的方法。

```java

```
