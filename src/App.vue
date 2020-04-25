<template>
<div id="app">
		<div class="sticky-top">
			<nav class="navbar">
				<input type="checkbox" name="check" id="check">
				<label for="check">
					<i class="butn"></i>
					<i class="fas fa-bars" id="btn"></i>
					<i class="fas fa-times" id="cancel"></i>
				</label>
				<ul>
					<li><a href="#">Home</a></li>
					<li><a href="#">Services</a></li>
					<li><a href="#">Customers</a></li>
					<li><a href="#">Income</a></li>
					<li><a href="#">Expenses</a></li>
				</ul>
			</nav>
			<div>
				<div class="days">
					<div></div>
					<div>mon</div>
					<div class="day_working_today">tue</div>
					<div>wed</div>
					<div>thu</div>
					<div>fri</div>
					<div>sat</div>
					<div>san</div>
				</div>
			</div>
		</div>
		<div class="tasks">
			<div v-bind:style="{ color: activeColor, fontSize: fontSize + 'px', height: h + 'vh' }" class="hours first">
				<div style="height: 20vh">00</div>
				<test-div></test-div>
				<div>02</div>
				<div>03</div>
				<div>04</div>
				<div>05</div>
				<div>06</div>
				<div>07</div>
				<div>08</div>
				<div>09</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
			<div class="hours">
				<div>1</div>
				<div>2</div>
				<div>3</div>
				<div>4</div>
				<div>5</div>
				<div>6</div>
				<div>7</div>
				<div>8</div>
				<div>9</div>
				<div>10</div>
				<div>11</div>
				<div>12</div>
				<div>13</div>
				<div>14</div>
				<div>15</div>
				<div>16</div>
				<div>17</div>
				<div>18</div>
				<div>19</div>
				<div>20</div>
				<div>21</div>
				<div>22</div>
				<div>23</div>
				<div>24</div>
			</div>
		</div>
	</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
