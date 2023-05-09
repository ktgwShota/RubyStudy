x = 2
y = 3

puts x + y

//

x = 2
y = 2
z = 3.14

puts x * y * z

//

x = "Ruby"

puts x

//

x = "abv"
y = "edf"

puts x + y

//

x = "123"
y = "456"

puts x.to_i + y.to_i

//

x = 300
y = 100
z = x + y * 2

puts "コーヒー："  + x.to_s + "円"
puts "合計：" + z.to_s  + "円"

//

a = 2

if a < 365
puts "365より小さい"
end

if a == 1 + 1
puts "i + 1 と等しい"
end

//

season = "春"
if season != "夏"
puts "あんまんたべたい"
end

// 

season = "夏"
if season == "夏"
puts "かき氷食べたい" 
puts "麦茶飲みたい" 
end 
puts "かき氷食べたい\n麦茶飲みたい" 

//

wallet = 100
if wallet >= 120
puts "ジュースを買おう"
else
puts "お金じゃ買えない幸せがたくさんあるんだ" 
end

//

x = 200
if x <= 0 || x >= 100
puts "範囲外です"
end

//

x = 0
y = -1
z = 1

if x > 0 || y > 0 || z > 0 
puts "正の数です"
end

//

season = "春"

case season
when "春"
puts "アイスを買っていこう！"
when "夏"
puts "かき氷を買っていこう！"
else
puts "あんまんを買っていこう"
end

//

x = "カフェラテ"
y = "モカ"
z = "フラペチーノ"

puts x
2.times { puts y }
puts x
2.times { puts y }
puts z

//

p ["コーヒー","カフェラテ"]

//

drinks = ["コーヒー","カフェラテ","モカ"]
puts drinks[1]
puts drinks.first
puts drinks.last

//

x = ["コーヒー","カフェラテ"]
x.push("モカ")
puts x

y = [2,3]
y.unshift(1)
puts y

puts [1,2] + [3,4]

//

x = ["ティーラテ","カフェラテ","抹茶ラテ"]
x.each do |y| 
puts y + "でお願いします"
end

//

x = 0
num = [1,2,3]
num.each do |n|
x += n
puts x
end

//

x = ["ティーラテ","カフェラテ","抹茶ラテ"]
x = []
puts x
//

x = ["コーヒー","カフェラテ"]
puts x.size

//

x = [1,2,3,4,5]

puts x.sum

//

x = ["モカ","カフェラテ","モカ"]
puts x.uniq

//

x = ["モカ","カフェラテ","カプチーノ"]
puts x.sample

//

x = ["大吉","中吉","末吉","凶"]
puts x.sample

//

x = [100,50,300]
puts x.sort

//

x = [100,50,300]
puts x.reverse

//

puts "cba".reverse

//

x = ["100","50","300"]
puts y = x.join(",")

z = y.split(",")
puts z

//

x = [1,2,3]
x.map do |y|
z = y * 3
puts z
end

//

x = ["abc","xyz"]
x.map do |y| 
puts y.reverse
end

//

x = ["aya","achi","Tama"]
z = []
x.map do |y|
z.push(y.downcase)
end
puts z

//

menu = {coffee: 300, caffe_latte: 400}
puts menu[:caffe_latte]

//

menu = {"モカ" => "チョコレートシロップとミルク入り", "カフェラテ" => "ミルク入り"}
puts menu["モカ"]

//

menu = {coffee: 300, caffe_latte: 400}
menu[:tea] = 300
menu.delete(:coffee)
puts menu

if menu[:tea].nil?
puts "紅茶はありませんか？"
end

if menu[:caffe_latte] <= 500
puts "カフェラテください"
end

//

hash = {}
array = "caffelatte"

array.chars.each do |i|
  if hash[i].nil?
    hash[i] = 1
  else
    hash[i] += 1
  end
end

puts hash

//

menu = {"コーヒー" => 300, "カフェラテ" => 400}

menu.each do |x,y|
  puts x + "-" + y.to_s + "円"
end

//

menu = {"コーヒー" => 300, "カフェラテ" => 400}

menu.each do |x,y|
  if y >= 350
    puts x + "-" + y.to_s + "円"
  end
end

menu = {}

menu.each do |x,y|
    puts x + "-" + y.to_s + "円" if y >= 350
end

menu = {"コーヒー" => 300, "カフェラテ" => 400}
array = []

menu.each do |x,y| 
array.push(x)
end

p array

//

def order 
  puts "カフェラテください"
end

order()

//

def area
  return 3 * 3
end

puts area()

//

def dice 
  x = [1,2,3,4,5,6]
  return x.sample
end

puts dice()

//

def order2 x
  puts x + "をください"
end

order2("カフェラテ")
order2("")

//

def dice2 
  x = [1,2,3,4,5,6]
  result = x.sample
  puts result
  if result == 1
    puts "もう1回"
    puts x.sample
  end
end

//

def prise item,size = "ショート"
  x = 300
  y = 400

  case size
    when "ショート"
      x += 0
      y += 0
    when "トール"
      x += 50
      y += 50
    when "ベンディ"
      x += 100
      y += 100
  end

  if item == "コーヒー" 
    return x
  elsif item = "カフェラテ"
    return y
  end
end

puts prise("カフェラテ")

//

def order3
  drink = "コーヒー"
  puts "#{drink}をください"
end
order3

//

hash = {:coffee => 300, :caffe_latte => 400}
p hash.class

//

instance = Hash.new
p instance

//

class CaffeLatte
end

caffelatte = CaffeLatte.new
p caffelatte.class

class Item
  def name
    "チーズケーキ"
  end
end

p Item.new.name

//

class Item2
  def name=(text)
  @name = text
  end
  def name 
  puts @name
  end
end

item = Item2.new
item.name=("チーズケーキ")
item.name

//

class Item3
  def initialize(x)
  @name = x
  end
  def name 
    puts @name
  end
end
item1 = Item3.new("マフィン")
item2 = Item3.new("スコーン")
item1.name
item2.name

//

class Drink
  def todays_special
    "ホワイトモカ"
  end
end

drink = Drink.new
puts drink.todays_special

//

class Item4
  def name
    @name
  end
  def name=(text)
    @name = text
  end
end

class Food < Item4 
end

food = Food.new
food.name = "チーズケーキ"
puts food.name

module ChocolateChip
  def Chocolate_chip
    @name += "チョコレートチップ"
  end
end

class Drink1
  include ChocolateChip
  def initialize(name)
    @name = name
  end
  def name
    @name
  end
end

drink1 = Drink1.new("モカ")
drink1.Chocolate_chip
puts drink1.name

module EspressoShot
  Prise = 100
end

puts EspressoShot::Prise

module WhippedCream
  def info
    "トッピング用ホイップクリーム"
  end
end

class Info
  extend WhippedCream
end

puts Info.info


