# script.xxx.lua
ffvpn= "https://vpn.uibe.edu.cn/por/phone_index.csp?rnd=0.23178949332658605#https%3A%2F%2Fvpn.uibe.edu.cn%2F" 
PW = gg.prompt({'🔒 Input password: '},{[1]=''},{[1]='MR HACKER YT'})
if not PW then return
end 
if PW[1] == "" then gg.alert("😡 SUBSCRIBE MR HACKER YT😡") os.exit() end
if PW[1] =="2345" then 
 gg.toast('CREDIT INDIAN@ LEGION')
else 
 gg.alert("MADRCHOD PASWARD SHI DAAL") return end
x=(tostring(gg.makeRequest(ffvpn))) 
if not x  or not x:sub(1,20) then  
gg.alert("Hi","GO") 
else 
while  #(x)<100  or x:find( "SSL" ) or x:find("I/O") or x:find("javax") do  
gg.alert("Turn off HTTPCanary\nStop Lichering!") 
print("go fuck yourself") 
os.exit() 
end 
end


gg.sleep(500)
gg.toast("🇮🇳□□□□□□□□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■□□□□□□□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■□□□□□□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■□□□□□□□□□□□□□")
gg.sleep(100)
gg.toast("■■■■□□□□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■□□□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■□□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■□□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■□□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■□□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■□□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■■□□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■■■□□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■■■■□□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■■■■■□□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■■■■■■□🇮🇳")
gg.sleep(100)
gg.toast("🇮🇳■■■■■■■■■■■■■■■■🇮🇳")
gg.sleep(100)

gg.alert(" \n🇮🇳IMPORTANT NOTICE BY MR HACKER  \n      —————————————————————————\n 🇮🇳WE DO NOT GUARANTEE FOR YOUR ACCOUNTS \n WE ALSO RECOMMEND PLAYING ON EMPTY NEW ACCOUNTS.🇮🇳      \n------------------------------------------------------ \n🇮🇳 THIS SCPRIT MADE BY MR HACKER 🇮🇳                        \n🇮🇳Sᴄʀɪᴘᴛ Wᴏʀᴋ Aʟʟ Dᴇᴠɪᴄᴇ      \n [🌺 WELCOME GUYS🌺] ")                                              
                                                     
function SearchWrite(Search, Write, Type) gg.clearResults() gg.setVisible(false) gg.searchNumber(Search[1][1], Type) local count = gg.getResultCount() local result = gg.getResults(count) gg.clearResults() local data = {} local base = Search[1][2] if (count > 0) then for i, v in ipairs(result) do v.isUseful = true end for k=2, #Search do local tmp = {} local offset = Search[k][2] - base local num = Search[k][1] for i, v in ipairs(result) do tmp[#tmp+1] = {} tmp[#tmp].address = v.address + offset tmp[#tmp].flags = v.flags end tmp = gg.getValues(tmp) for i, v in ipairs(tmp) do if ( tostring(v.value) ~= tostring(num) ) then result[i].isUseful = false end end end for i, v in ipairs(result) do if (v.isUseful) then data[#data+1] = v.address end end if (#data > 0) then gg.toast("🌺MR HACKER OP🌺"..#data.."🌺MR HACKER OP🌺") local t = {} local base = Search[1][2] for i=1, #data do for k, w in ipairs(Write) do offset = w[2] - base t[#t+1] = {} t[#t].address = data[i] + offset t[#t].flags = Type t[#t].value = w[1] if (w[3] == true) then local item = {} item[#item+1] = t[#t] item[#item].freeze = true gg.addListItems(item) end end end gg.setValues(t) else gg.toast("🌺MR HACKER OP🌺", false) return false end else gg.toast("🌺MR HACKER OP🌺") return false end end
function split(szFullString, szSeparator) local nFindStartIndex = 1 local nSplitIndex = 1 local nSplitArray = {} while true do local nFindLastIndex = string.find(szFullString, szSeparator, nFindStartIndex) if not nFindLastIndex then nSplitArray[nSplitIndex] = string.sub(szFullString, nFindStartIndex, string.len(szFullString)) break end nSplitArray[nSplitIndex] = string.sub(szFullString, nFindStartIndex, nFindLastIndex - 1) nFindStartIndex = nFindLastIndex + string.len(szSeparator) nSplitIndex = nSplitIndex + 1 end return nSplitArray end function xgxc(szpy, qmxg) for x = 1, #(qmxg) do xgpy = szpy + qmxg[x]["offset"] xglx = qmxg[x]["type"] xgsz = qmxg[x]["value"] gg.setValues({[1] = {address = xgpy, flags = xglx, value = xgsz}}) xgsl = xgsl + 1 end end function xqmnb(qmnb) gg.clearResults() gg.setRanges(qmnb[1]["memory"]) gg.searchNumber(qmnb[3]["value"], qmnb[3]["type"]) if gg.getResultCount() == 0 then gg.toast(qmnb[2]["name"] .. "🌺MR HACKER🌺") else gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"]) gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"]) gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"]) if gg.getResultCount() == 0 then gg.toast(qmnb[2]["name"] .. "🌺MR HACKER🌺") else sl = gg.getResults(999999) sz = gg.getResultCount() xgsl = 0 if sz > 999999 then sz = 999999 end for i = 1, sz do pdsz = true for v = 4, #(qmnb) do if pdsz == true then pysz = {} pysz[1] = {} pysz[1].address = sl[i].address + qmnb[v]["offset"] pysz[1].flags = qmnb[v]["type"] szpy = gg.getValues(pysz) pdpd = qmnb[v]["lv"] .. ";" .. szpy[1].value szpd = split(pdpd, ";") tzszpd = szpd[1] pyszpd = szpd[2] if tzszpd == pyszpd then pdjg = true pdsz = true else pdjg = false pdsz = false end end end if pdjg == true then szpy = sl[i].address xgxc(szpy, qmxg) xgjg = true end end if xgjg == true then gg.toast(qmnb[2]["name"] .. "🌺MR HACKER🌺" .. xgsl .. "🌺MR HACKER🌺") else gg.toast(qmnb[2]["name"] .. "🌺MR HACKER🌺") end end end end
local jldz={}function KYXG(DZ,XGSJ,GNM,JLDZ)local t={}for i=1,#DZ do for k,w in ipairs(XGSJ) do offset=w[1]*4 t[#t+1]={}t[#t].address=DZ[i]+offset t[#t].flags=w[2]t[#t].value=w[3]if(w[4]==true)then local item={}item[#item+1]=t[#t]item[#item].freeze=true gg.addListItems(item)end end end gg.setValues(t)gg.toast(GNM.."🌺MR HACKER🌺")end function KY_ZZ(NCLX,SSSJ,XGSJ,GNM)gg.setVisible(false)if jldz[NCLX[4]]==nil then gg.clearResults()gg.setRanges(NCLX[1])gg.searchNumber(NCLX[2],NCLX[3])local count=gg.getResultCount()local result=gg.getResults(count)gg.clearResults()local data={}if(count>0)then for i,v in ipairs(result) do v.isUseful=true end for k=1,#SSSJ do local tmp={}local offset=SSSJ[k][1]*4 local num=SSSJ[k][2]for i,v in ipairs(result) do tmp[#tmp+1]={}tmp[#tmp].address=v.address+offset tmp[#tmp].flags=v.flags end tmp=gg.getValues(tmp)for i,v in ipairs(tmp) do if (v.value~=num)then result[i].isUseful=false end end end for i,v in ipairs(result) do if (v.isUseful)then data[#data+1]=v.address end end if data[1]==nil then gg.toast("🌺MR HACKER🌺")else if NCLX[4]~=false then jldz[NCLX[4]]=data KYXG(data,XGSJ,GNM,"🌺MR HACKER🌺")else KYXG(data,XGSJ,GNM,"🌺MR HACKER🌺")end end else gg.toast(GNM.."🌺MR HACKER🌺")end else KYXG(jldz[NCLX[4]],XGSJ,GNM,"🌺MR HACKER 🌺")end end
-------------------------------------------------


HOME = 0

function Hh()
active = 0
gg.setVisible(false)
H = {
    "『×🇮🇳×』",
    "『×🌺×』",
    "『×🥀×』",
    "『×🍓×』",
    "『×🌹×』",
    "『×♥️×』", 
    "『×💋×』",
  }
  O = math.random(7)
  G = H[O]
HM = gg.choice({
G .. "Bypass " .. G,
G .. "SCRIPT V1 【⚠️UNSAFE⚠️】" .. G,
G .. "SCRIPT V2 【☢️SAFE☢️】" .. G,
G .. "SCPRIT V3【☣️SAFE☣️】" .. G,
G .. "Exit" .. G,
}, nil, os.date("⏰⟮ %d/%m/%y | %X ⟯ ⏰"))
if HM == 1 then Home() end
if HM == 2 then Home2() end
if HM == 3 then Home3() end
if HM == 4 then Home4() end
if HM == 5 then Exit() end
end
function Home()
SN8 = gg.choice({
"Clear Report 🇮🇳",
"Bypass V1 🇮🇳",
"💋Back💋",
},nil, os.date("⏰⟮ %d/%m/%y | %X ⟯ ⏰\n"))
if SN8 == 1 then X1() end
if SN8 == 2 then X2() end
if SN8 == 3 then HOME() end
XGCK = -1
end

function Home4()
  menu = gg.multiChoice({
    "🔫AimLock 100m(don't work all phone)",
    "🙆Anten Player",
    "🔎Zoom8X(AllGun)",
    "⚔️OneClick(PVP)",
    "🕳️Burrowed+✈️Fly Car",
    "🤺White Boy+WallHack",
    "🔭Scope ↕️",
    "🎩Magic Bullet",
    "🌀Menu Norecoil",
    "⚡Fast Change",
    "⚡Fast Shot(unsafe)",
    "👿Anti Boss Anti Turret(unsafe)",
    "🛏️️Anten Bed",
    "🗿Anten Ore Sulfur",
    "💰️Anten Item Loot",
    "🌲️No Trees",
    "🤽Underwater",
    "🏘️Looking Through the House",
    "🏎Speed Car️",
    "⚪Remove map(Unsafe)",
    "👁️iPad View",
    "⏩Speed Fast Farm",
    "🕊️Fly With Hoof",
    "🙆Anten Loop",
    "☀️Time Day And Lock Time",
    "🚶Go Through Wall",
    "🌊Swimming in the Sky(Fly)",
    "💥Bazoka Shoot Through Walls",
    "👻Leaving the Soul(unsafe)",
    "🦘Long Jump",
    "🧱Forced Construction",
    "💉Anti Dead",
    "Bᴀᴄᴋ"
  }, nil, os.date("⏰⟮ %d/%m/%y | %X ⟯ ⏰"))
  if menu == nil then
  else
    if menu[1] == true then
      aimlock()
    end
    if menu[2] == true then
      antenb()
    end
    if menu[3] == true then
      luffy()
    end
    if menu[4] == true then
      view()
    end
    if menu[5] == true then
      aim32()
    end
    if menu[6] == true then
      boy()
    end
    if menu[7] == true then
      x10()
    end
    if menu[8] == true then
      mgc()
    end
    if menu[9] == true then
      nrc()
    end
    if menu[10] == true then
      fast()
    end
    if menu[11] == true then
      shot()
    end
    if menu[12] == true then
      anti()
    end
    if menu[13] == true then
      bed()
    end
    if menu[14] == true then
      ore()
    end
    if menu[15] == true then
      loot()
    end
    if menu[16] == true then
      time()
    end
    if menu[17] == true then
      nuoc()
    end
    if menu[18] == true then
      nha()
    end
    if menu[19] == true then
      moto()
    end
    if menu[20] == true then
      map()
    end
    if menu[21] == true then
      view2()
    end
    if menu[22] == true then
      speed()
    end
    if menu[23] == true then
      fly()
    end
    if menu[24] == true then
      anten()
    end
    if menu[25] == true then
      xc2()
    end
    if menu[26] == true then
      st()
    end
    if menu[27] == true then
      boi()
    end
    if menu[28] == true then
      shoot()
    end
    if menu[29] == true then
      soul()
    end
    if menu[30] == true then
      jump()
    end
    if menu[31] == true then
      build()
    end
    if menu[32] == true then
      antidead()
    end
    if menu[33] == true then
      index()
    end
  end
end

function aimlock()
  F = gg.alert("Aimlock 100m", "ON", "OFF")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("-6.171913993364983E27;-1.0061304023208683E28;-1.220370790326068E21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("-1.0061304023208683E28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(9990)
    gg.editAll("10.000123456789", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(16384)
    gg.searchNumber("-6.171913993364983E27;-1.0061304023208683E28;-1.220370790326068E21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("-1.0061304023208683E28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(9990)
    gg.editAll("10.000123456789", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("10.000123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("10.000123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(9990)
    gg.editAll("-1.0061304023208683E28", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(16384)
    gg.searchNumber("10.000123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("10.000123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(9990)
    gg.editAll("-1.0061304023208683E28", gg.TYPE_FLOAT)
    gg.clearResults()
  end
end

function anten()
  local L0_71, L1_72, L2_73, L3_74
  L0_71 = 1
  L1_72 = 50
  for i = 1, 50 do
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("-0.9855342507362366", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("-500", gg.REGION_C_BSS)
    gg.clearResults()
    gg.clearResults()
    qmnb = {
      {memory = 1048576},
      {name = "ON"},
      {value = 4.4570662209845934E-29, type = 16},
      {
        lv = 2.2500014305114746,
        offset = 4,
        type = 16
      }
    }
    qmxg = {
      {
        value = 2.26000142097,
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("1.58116769791", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("-999", gg.REGION_C_BSS)
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("0.16947640479", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("-999", gg.REGION_C_BSS)
    gg.clearResults()
    gg.sleep(1000)
  end-- for | Ghost
end

function antenb()
  gg.clearResults()
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("-0.9855342507362366", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("-500", gg.REGION_C_BSS)
  gg.clearResults()
  gg.clearResults()
  qmnb = {
    {memory = 1048576},
    {name = "ON"},
    {value = 4.4570662209845934E-29, type = 16},
    {
      lv = 2.2500014305114746,
      offset = 4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 2.26000142097,
      offset = 4,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("1.58116769791", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("-999", gg.REGION_C_BSS)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("0.16947640479", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("-999", gg.REGION_C_BSS)
  gg.clearResults()
end

function x10()
  menu1 = gg.choice({
    "⭐[Scope ↕️Use Bazoka, Grenade Launcher]",
    "⭐[Scope In Sky]",
    "⭐[Sxope In Under Map(Unsafe)]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[If it does work go out and back in]")
  if menu1 == 1 then
    bar()
  end
  if menu1 == 2 then
    cao()
  end
  if menu1 == 3 then
    dow()
  end
  if menu1 == 4 then
    index()
  end
  GLWW = -1
end

function bar()
  Q = gg.prompt({
    "No Scope: [-50;80] "
  }, {0}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 400, type = 16},
      {
        lv = 8,
        offset = -8,
        type = 16
      },
      {
        lv = 2,
        offset = -4,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 56,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function cao()
  F = gg.alert("Shoot In Sky", "Scope", "OFF", "No Scope")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 400, type = 16},
      {
        lv = 8,
        offset = -8,
        type = 16
      },
      {
        lv = 2,
        offset = -4,
        type = 16
      },
      {
        lv = 0,
        offset = 48,
        type = 16
      }
    }
    qmxg = {
      {
        value = -0.9123456789,
        offset = 48,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("0.9123456789", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("-0.9123456789", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 3 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 400, type = 16},
      {
        lv = 8,
        offset = -8,
        type = 16
      },
      {
        lv = 2,
        offset = -4,
        type = 16
      },
      {
        lv = 0,
        offset = 56,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0.9123456789,
        offset = 56,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function dow()
  F = gg.alert("Scope In Under Map", "Scope", "OFF", "No Scope")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 400, type = 16},
      {
        lv = 8,
        offset = -8,
        type = 16
      },
      {
        lv = 2,
        offset = -4,
        type = 16
      },
      {
        lv = 0,
        offset = 48,
        type = 16
      }
    }
    qmxg = {
      {
        value = 3.40123456,
        offset = 48,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("3.40123456", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("-3.40123456", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 3 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 400, type = 16},
      {
        lv = 8,
        offset = -8,
        type = 16
      },
      {
        lv = 2,
        offset = -4,
        type = 16
      },
      {
        lv = 0,
        offset = 56,
        type = 16
      }
    }
    qmxg = {
      {
        value = -3.40123456,
        offset = 56,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function boy()
  menu1 = gg.choice({
    "⭐[Wall Hack]",
    "⭐[Body White]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Wallhack opens low graphics]")
  if menu1 == 1 then
    wall()
  end
  if menu1 == 2 then
    nguoi()
  end
  if menu1 == 3 then
    index()
  end
  GLWW = -1
end

function wall()
  F = gg.alert("[Wallhack Need Lower Shadows]", "V2", "OFF", "V1")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(1048576)
    gg.searchNumber("2.2500064373", gg.TYPE_FLOAT)
    gg.getResults(9000)
    gg.editAll("2.2600064373", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(1048576)
    gg.searchNumber("2.26000142097", gg.TYPE_FLOAT)
    gg.getResults(9000)
    gg.editAll("2.25000143051", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(1048576)
    gg.searchNumber("2.2600064373", gg.TYPE_FLOAT)
    gg.getResults(9000)
    gg.editAll("2.2500064373", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("5.127597087642792E29", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("5.127597087642792E-29", gg.TYPE_FLOAT)
  elseif F == 3 then
    qmnb = {
      {memory = 1048576},
      {name = "ON"},
      {value = 4.4570662209845934E-29, type = 16},
      {
        lv = 2.2500014305114746,
        offset = 4,
        type = 16
      }
    }
    qmxg = {
      {
        value = 2.26000142097,
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("5.127597087642792E-29", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("5.127597087642792E29", gg.TYPE_FLOAT)
  end
end

function nguoi()
  F = gg.alert("WhiteBoy Need Graphics Medium", "ON", "OFF")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 82.5, type = 16},
      {
        lv = 15,
        offset = 4,
        type = 16
      },
      {
        lv = 5,
        offset = 12,
        type = 16
      },
      {
        lv = 0.75,
        offset = 1316,
        type = 16
      }
    }
    qmxg = {
      {
        value = 20.0123456789,
        offset = 1316,
        type = 16
      }
    }
    xqmnb(qmnb)
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("20.0123456789", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0.75", gg.TYPE_FLOAT)
    gg.clearResults()
  end
end

function aim32()
  menu1 = gg.choice({
    "⭐[Map Old]",
    "⭐[Map New]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Burrowed and Flying Car]")
  if menu1 == 1 then
    dontho1()
  end
  if menu1 == 2 then
    dontho2()
  end
  if menu1 == 3 then
    index()
  end
  GLWW = -1
end

function dontho1()
  F = gg.alert("Burrowed(can build under map)", "Burrowed", "OFF", "Fly Car")
  if F == 1 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = -0.7071068286895752,
        offset = -40,
        type = 16
      },
      {
        lv = 0.7071068286895752,
        offset = -28,
        type = 16
      },
      {
        lv = 0,
        offset = -20,
        type = 16
      }
    }
    qmxg = {
      {
        value = -1.64123456789,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("-1.64123456789", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("5.40123456789", gg.TYPE_FLOAT)
    gg.getResults(900)
    gg.editAll("0", gg.TYPE_FLOAT)
  elseif F == 3 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = -0.7071068286895752,
        offset = -40,
        type = 16
      },
      {
        lv = 0.7071068286895752,
        offset = -28,
        type = 16
      },
      {
        lv = 0,
        offset = -20,
        type = 16
      }
    }
    qmxg = {
      {
        value = 4.40123456789,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function dontho2()
  F = gg.alert("Burrowed(can build under map)", "Burrowed", "OFF", "Fly Car")
  if F == 1 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = -44,
        type = 16
      },
      {
        lv = 1,
        offset = -28,
        type = 16
      }
    }
    qmxg = {
      {
        value = -58.93824920654,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = -44,
        type = 16
      },
      {
        lv = 1,
        offset = -28,
        type = 16
      }
    }
    qmxg = {
      {
        value = -57.33824920654297,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 3 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = -44,
        type = 16
      },
      {
        lv = 1,
        offset = -28,
        type = 16
      }
    }
    qmxg = {
      {
        value = -54.03824920654,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function luffy()
  qmnb = {
    {memory = 32},
    {name = "50%"},
    {value = 48, type = 16},
    {
      lv = 0,
      offset = 4,
      type = 16
    },
    {
      lv = 0,
      offset = 8,
      type = 16
    },
    {
      lv = 0,
      offset = 12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 10,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "100%"},
    {value = 45, type = 16},
    {
      lv = 0,
      offset = 4,
      type = 16
    },
    {
      lv = 0,
      offset = 8,
      type = 16
    },
    {
      lv = 0,
      offset = 12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 10,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function mgc()
  menu1 = gg.choice({
    "⭐[Magic 30%]",
    "⭐[Magic 60%[+30%🧠]",
    "⭐[Magic 100%[Body]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Magic Bullet Menu]")
  if menu1 == 1 then
    mgc1()
  end
  if menu1 == 2 then
    mgc2()
  end
  if menu1 == 3 then
    mgc3()
  end
  if menu1 == 4 then
    index()
  end
  GLWW = -1
end

function mgc1()
  qmnb = {
    {memory = 32},
    {name = "10% Magic"},
    {value = 0.5400000214576721, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "30% Magic"},
    {value = 0.6899999976158142, type = 16},
    {
      lv = 0.1599999964237213,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "60% Magic"},
    {value = 0.47999998927116394, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "80% Magic"},
    {value = 0.44999998807907104, type = 16},
    {
      lv = 0.03999999910593033,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "100% Xong Magic"
    },
    {value = 0.3400000035762787, type = 16},
    {
      lv = 0.10999999940395355,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function mgc3()
  qmnb = {
    {memory = 32},
    {name = "10% Magic"},
    {value = 0.5400000214576721, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "30% Magic"},
    {value = 0.6899999976158142, type = 16},
    {
      lv = 0.1599999964237213,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "60% Magic"},
    {value = 0.47999998927116394, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "80% Magic"},
    {value = 0.44999998807907104, type = 16},
    {
      lv = 0.03999999910593033,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "100% Xong Magic"
    },
    {value = 0.3400000035762787, type = 16},
    {
      lv = 0.10999999940395355,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function mgc2()
  qmnb = {
    {memory = 32},
    {name = "10% magic"},
    {value = 0.5400000214576721, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "50% Magic"},
    {value = 0.44999998807907104, type = 16},
    {
      lv = 0.03999999910593033,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "100% Xong Magic"
    },
    {value = 0.3400000035762787, type = 16},
    {
      lv = 0.10999999940395355,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function nrc()
  menu1 = gg.choice({
    "⭐[Norecoil Custom]",
    "⭐[Norecoil 100%]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Norecoil Menu]")
  if menu1 == 1 then
    nrc1()
  end
  if menu1 == 2 then
    nrc2()
  end
  if menu1 == 3 then
    index()
  end
  GLWW = -1
end

function nrc1()
  menu1 = gg.choice({
    "⭐[M4-AKM-M762-QBZ]",
    "⭐[SMG-Uzi-Famas]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Norecoil Setting]")
  if menu1 == 1 then
    ar1()
  end
  if menu1 == 2 then
    smg1()
  end
  if menu1 == 3 then
    index()
  end
  GLWW = -1
end

function ar1()
  Q = gg.prompt({
    " Heart 🎯(Tâm🎯): [0;40] ",
    " Up ↕️(Giật↕️): [0;4] ",
    " Horizontal ↔️(Giật↔️): [0;4] "
  }, {
    20,
    2,
    2
  }, {
    "number",
    "number",
    "number"
  })
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {
        name = "[M4] Active ✅"
      },
      {value = 830, type = 16},
      {
        lv = 45,
        offset = -140,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -148,
        type = 16
      },
      {
        value = Q[1],
        offset = -144,
        type = 16
      },
      {
        value = 0,
        offset = -136,
        type = 16
      },
      {
        value = 0,
        offset = -124,
        type = 16
      },
      {
        value = Q[2],
        offset = 16,
        type = 16
      },
      {
        value = Q[3],
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {
        name = "[Qbz] Active ✅"
      },
      {value = 790, type = 16},
      {
        lv = 45,
        offset = -140,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -148,
        type = 16
      },
      {
        value = Q[1],
        offset = -144,
        type = 16
      },
      {
        value = 0,
        offset = -136,
        type = 16
      },
      {
        value = 0,
        offset = -124,
        type = 16
      },
      {
        value = Q[2],
        offset = 16,
        type = 16
      },
      {
        value = Q[3],
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {
        name = "[Akm M762] Active ✅"
      },
      {value = 735, type = 16},
      {
        lv = 50,
        offset = -140,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -148,
        type = 16
      },
      {
        value = Q[1],
        offset = -144,
        type = 16
      },
      {
        value = 0,
        offset = -136,
        type = 16
      },
      {
        value = 0,
        offset = -124,
        type = 16
      },
      {
        value = Q[2],
        offset = 16,
        type = 16
      },
      {
        value = Q[3],
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function smg1()
  Q = gg.prompt({
    " Heart 🎯(Tâm🎯): [0;40] ",
    " Up ↕️(Giật↕️): [0;4] ",
    " Horizontal ↔️(Giật↔️): [0;4] "
  }, {
    20,
    2,
    2
  }, {
    "number",
    "number",
    "number"
  })
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {
        name = "[Smg] Active ✅"
      },
      {value = 300, type = 16},
      {
        lv = 44,
        offset = -140,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -148,
        type = 16
      },
      {
        value = Q[1],
        offset = -144,
        type = 16
      },
      {
        value = 0,
        offset = -136,
        type = 16
      },
      {
        value = 0,
        offset = -124,
        type = 16
      },
      {
        value = Q[2],
        offset = 16,
        type = 16
      },
      {
        value = Q[3],
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {
        name = "[Uzi] Active ✅"
      },
      {value = 320, type = 16},
      {
        lv = 42,
        offset = -140,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -148,
        type = 16
      },
      {
        value = Q[1],
        offset = -144,
        type = 16
      },
      {
        value = 0,
        offset = -136,
        type = 16
      },
      {
        value = 0,
        offset = -124,
        type = 16
      },
      {
        value = Q[2],
        offset = 16,
        type = 16
      },
      {
        value = Q[3],
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {
        name = "[Famas] Active ✅"
      },
      {value = 360, type = 16},
      {
        lv = 42,
        offset = -140,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -148,
        type = 16
      },
      {
        value = Q[1],
        offset = -144,
        type = 16
      },
      {
        value = 0,
        offset = -136,
        type = 16
      },
      {
        value = 0,
        offset = -124,
        type = 16
      },
      {
        value = Q[2],
        offset = 16,
        type = 16
      },
      {
        value = Q[3],
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function nrc2()
  menu1 = gg.choice({
    "⭐[ALL-GUN]",
    "⭐[M4-AKM-M762-QBZ]",
    "⭐[SMG-Uzi-Famas]",
    "⭐[M249-Lewis-Pistol-Crossbow]",
    "⭐[Mini14-Semi-M24-K31]",
    "⭐[Shotgun-Bazoka-Grenade Launcher]",
    "⭐[OFF Norecoil Bazoka]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Norecoil 100% Menu]")
  if menu1 == 1 then
    all()
  end
  if menu1 == 2 then
    ar()
  end
  if menu1 == 3 then
    smg()
  end
  if menu1 == 4 then
    mg()
  end
  if menu1 == 5 then
    snipe()
  end
  if menu1 == 6 then
    sg()
  end
  if menu1 == 7 then
    bzk()
  end
  if menu1 == 8 then
    index()
  end
  GLWW = -1
end

function bzk()
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("99999.01234567", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("40.0123456789", gg.REGION_C_BSS)
  gg.clearResults()
end

function all()
  qmnb = {
    {memory = 32},
    {
      name = "[ M4 ] Active ✅"
    },
    {value = 830, type = 16},
    {
      lv = 12,
      offset = -148,
      type = 16
    },
    {
      lv = 24,
      offset = -144,
      type = 16
    },
    {
      lv = 45,
      offset = -140,
      type = 16
    },
    {
      lv = 3.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[Akm M762] Active ✅"
    },
    {value = 735, type = 16},
    {
      lv = 50,
      offset = -140,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Qbz ] Active ✅"
    },
    {value = 790, type = 16},
    {
      lv = 12,
      offset = -148,
      type = 16
    },
    {
      lv = 27,
      offset = -144,
      type = 16
    },
    {
      lv = 45,
      offset = -140,
      type = 16
    },
    {
      lv = 3.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ M249 ] Active ✅"
    },
    {value = 480, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 55,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Lewis ] Active ✅"
    },
    {value = "480.0", type = 16},
    {
      lv = "20.0",
      offset = -148,
      type = 16
    },
    {
      lv = "40.0",
      offset = -144,
      type = 16
    },
    {
      lv = "6.0",
      offset = -136,
      type = 16
    },
    {
      lv = "60.0",
      offset = -120,
      type = 16
    },
    {
      lv = "0.5",
      offset = -100,
      type = 16
    },
    {
      lv = "4.0",
      offset = 16,
      type = 16
    },
    {
      lv = "4.0",
      offset = 24,
      type = 16
    },
    {
      lv = "1.0",
      offset = 160,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -120,
      type = 16
    },
    {
      value = 0,
      offset = -100,
      type = 16
    },
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    },
    {
      value = 0,
      offset = 160,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Smg ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 32,
      offset = -144,
      type = 16
    },
    {
      lv = 44,
      offset = -140,
      type = 16
    },
    {
      lv = 2.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Uzi ] Active ✅"
    },
    {value = 320, type = 16},
    {
      lv = 16,
      offset = -148,
      type = 16
    },
    {
      lv = 34,
      offset = -144,
      type = 16
    },
    {
      lv = 42,
      offset = -140,
      type = 16
    },
    {
      lv = 3,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Famas ] Active ✅"
    },
    {value = 360, type = 16},
    {
      lv = 14,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 42,
      offset = -140,
      type = 16
    },
    {
      lv = 2.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Bazoka ] Active ✅"
    },
    {value = 278, type = 16},
    {
      lv = 15,
      offset = -196,
      type = 16
    },
    {
      lv = 30,
      offset = -192,
      type = 16
    },
    {
      lv = 45,
      offset = -188,
      type = 16
    },
    {
      lv = 35,
      offset = -172,
      type = 16
    },
    {
      lv = 4,
      offset = -84,
      type = 16
    },
    {
      lv = 4,
      offset = -80,
      type = 16
    },
    {
      lv = 40,
      offset = -48,
      type = 16
    },
    {
      lv = 20,
      offset = -32,
      type = 16
    },
    {
      lv = 10,
      offset = -24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -196,
      type = 16
    },
    {
      value = 0,
      offset = -192,
      type = 16
    },
    {
      value = 0,
      offset = -188,
      type = 16
    },
    {
      value = 0,
      offset = -172,
      type = 16
    },
    {
      value = 0,
      offset = -84,
      type = 16
    },
    {
      value = 0,
      offset = -80,
      type = 16
    },
    {
      value = 99999.01234567,
      offset = -48,
      type = 16
    },
    {
      value = 0,
      offset = -32,
      type = 16
    },
    {
      value = 0,
      offset = -24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Grenade Launcher ] Active ✅"
    },
    {value = 400, type = 16},
    {
      lv = 24,
      offset = -188,
      type = 16
    },
    {
      lv = 24,
      offset = -184,
      type = 16
    },
    {
      lv = 24,
      offset = -180,
      type = 16
    },
    {
      lv = 35,
      offset = -164,
      type = 16
    },
    {
      lv = 4,
      offset = -76,
      type = 16
    },
    {
      lv = 4,
      offset = -72,
      type = 16
    },
    {
      lv = 25,
      offset = -40,
      type = 16
    },
    {
      lv = 20,
      offset = -24,
      type = 16
    },
    {
      lv = 10,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -188,
      type = 16
    },
    {
      value = 0,
      offset = -184,
      type = 16
    },
    {
      value = 0,
      offset = -180,
      type = 16
    },
    {
      value = 0,
      offset = -164,
      type = 16
    },
    {
      value = 0,
      offset = -76,
      type = 16
    },
    {
      value = 0,
      offset = -72,
      type = 16
    },
    {
      value = 99999,
      offset = -40,
      type = 16
    },
    {
      value = 0,
      offset = -24,
      type = 16
    },
    {
      value = 0,
      offset = -12,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Mini-14 ] Active ✅"
    },
    {value = 830, type = 16},
    {
      lv = 13,
      offset = -148,
      type = 16
    },
    {
      lv = 33,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 6,
      offset = -136,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("40.0123456789", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("99999.01234567", gg.REGION_C_BSS)
  gg.clearResults()
  qmnb = {
    {memory = 32},
    {
      name = "[ Semi ] Active ✅"
    },
    {value = 710, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 35,
      offset = -144,
      type = 16
    },
    {
      lv = 55,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Simple Shotgun ] Active ✅"
    },
    {value = 45, type = 16},
    {
      lv = "3.0",
      offset = 12,
      type = 16
    },
    {
      lv = "60.0",
      offset = 28,
      type = 16
    },
    {
      lv = "300.0",
      offset = 148,
      type = 16
    },
    {
      lv = "13.0",
      offset = 164,
      type = 16
    },
    {
      lv = "8.0",
      offset = 192,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 12,
      type = 16
    },
    {
      value = 0,
      offset = 28,
      type = 16
    },
    {
      value = 99999.011,
      offset = 148,
      type = 16
    },
    {
      value = 0,
      offset = 164,
      type = 16
    },
    {
      value = 0,
      offset = 192,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Double Shotgun ] Active ✅"
    },
    {value = 45, type = 16},
    {
      lv = "3.0",
      offset = 12,
      type = 16
    },
    {
      lv = "60.0",
      offset = 28,
      type = 16
    },
    {
      lv = "300.0",
      offset = 148,
      type = 16
    },
    {
      lv = "15.0",
      offset = 164,
      type = 16
    },
    {
      lv = "8.0",
      offset = 192,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 12,
      type = 16
    },
    {
      value = 0,
      offset = 28,
      type = 16
    },
    {
      value = 99999.012,
      offset = 148,
      type = 16
    },
    {
      value = 0,
      offset = 164,
      type = 16
    },
    {
      value = 0,
      offset = 192,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Crossbow ] Active ✅"
    },
    {value = 50, type = 16},
    {
      lv = 20,
      offset = -8,
      type = 16
    },
    {
      lv = 40,
      offset = -4,
      type = 16
    },
    {
      lv = 10,
      offset = 16,
      type = 16
    },
    {
      lv = 40,
      offset = 140,
      type = 16
    },
    {
      lv = 7,
      offset = 156,
      type = 16
    },
    {
      lv = 10,
      offset = 164,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -8,
      type = 16
    },
    {
      value = 0,
      offset = -4,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 99,
      offset = 140,
      type = 16
    },
    {
      value = 0,
      offset = 156,
      type = 16
    },
    {
      value = 0,
      offset = 164,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Pistol ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 5,
      offset = 16,
      type = 16
    },
    {
      lv = 9,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Pistol Black ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 5,
      offset = 16,
      type = 16
    },
    {
      lv = 9,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ SniperM24 ] Active ✅"
    },
    {value = 912, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ SniperK31 ] Active ✅"
    },
    {value = 720, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function ar()
  qmnb = {
    {memory = 32},
    {
      name = "[ M4 ] Active ✅"
    },
    {value = 830, type = 16},
    {
      lv = 12,
      offset = -148,
      type = 16
    },
    {
      lv = 24,
      offset = -144,
      type = 16
    },
    {
      lv = 45,
      offset = -140,
      type = 16
    },
    {
      lv = 3.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[Akm M762] Active ✅"
    },
    {value = 735, type = 16},
    {
      lv = 50,
      offset = -140,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Qbz ] Active ✅"
    },
    {value = 790, type = 16},
    {
      lv = 12,
      offset = -148,
      type = 16
    },
    {
      lv = 27,
      offset = -144,
      type = 16
    },
    {
      lv = 45,
      offset = -140,
      type = 16
    },
    {
      lv = 3.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function mg()
  qmnb = {
    {memory = 32},
    {
      name = "[ M249 ] Active ✅"
    },
    {value = 480, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 55,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Lewis ] Active ✅"
    },
    {value = "480.0", type = 16},
    {
      lv = "20.0",
      offset = -148,
      type = 16
    },
    {
      lv = "40.0",
      offset = -144,
      type = 16
    },
    {
      lv = "6.0",
      offset = -136,
      type = 16
    },
    {
      lv = "60.0",
      offset = -120,
      type = 16
    },
    {
      lv = "0.5",
      offset = -100,
      type = 16
    },
    {
      lv = "4.0",
      offset = 16,
      type = 16
    },
    {
      lv = "4.0",
      offset = 24,
      type = 16
    },
    {
      lv = "1.0",
      offset = 160,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -120,
      type = 16
    },
    {
      value = 0,
      offset = -100,
      type = 16
    },
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    },
    {
      value = 0,
      offset = 160,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Crossbow ] Active ✅"
    },
    {value = 50, type = 16},
    {
      lv = 20,
      offset = -8,
      type = 16
    },
    {
      lv = 40,
      offset = -4,
      type = 16
    },
    {
      lv = 10,
      offset = 16,
      type = 16
    },
    {
      lv = 40,
      offset = 140,
      type = 16
    },
    {
      lv = 7,
      offset = 156,
      type = 16
    },
    {
      lv = 10,
      offset = 164,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -8,
      type = 16
    },
    {
      value = 0,
      offset = -4,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 99,
      offset = 140,
      type = 16
    },
    {
      value = 0,
      offset = 156,
      type = 16
    },
    {
      value = 0,
      offset = 164,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Pistol Black ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 5,
      offset = 16,
      type = 16
    },
    {
      lv = 9,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Pistol ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 5,
      offset = 16,
      type = 16
    },
    {
      lv = 9,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function smg()
  qmnb = {
    {memory = 32},
    {
      name = "[ Smg ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 32,
      offset = -144,
      type = 16
    },
    {
      lv = 44,
      offset = -140,
      type = 16
    },
    {
      lv = 2.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Uzi ] Active ✅"
    },
    {value = 320, type = 16},
    {
      lv = 16,
      offset = -148,
      type = 16
    },
    {
      lv = 34,
      offset = -144,
      type = 16
    },
    {
      lv = 42,
      offset = -140,
      type = 16
    },
    {
      lv = 3,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Famas ] Active ✅"
    },
    {value = 360, type = 16},
    {
      lv = 14,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 42,
      offset = -140,
      type = 16
    },
    {
      lv = 2.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function sg()
  qmnb = {
    {memory = 32},
    {
      name = "[ Bazoka ] Active ✅"
    },
    {value = 278, type = 16},
    {
      lv = 15,
      offset = -196,
      type = 16
    },
    {
      lv = 30,
      offset = -192,
      type = 16
    },
    {
      lv = 45,
      offset = -188,
      type = 16
    },
    {
      lv = 35,
      offset = -172,
      type = 16
    },
    {
      lv = 4,
      offset = -84,
      type = 16
    },
    {
      lv = 4,
      offset = -80,
      type = 16
    },
    {
      lv = 40,
      offset = -48,
      type = 16
    },
    {
      lv = 20,
      offset = -32,
      type = 16
    },
    {
      lv = 10,
      offset = -24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -196,
      type = 16
    },
    {
      value = 0,
      offset = -192,
      type = 16
    },
    {
      value = 0,
      offset = -188,
      type = 16
    },
    {
      value = 0,
      offset = -172,
      type = 16
    },
    {
      value = 0,
      offset = -84,
      type = 16
    },
    {
      value = 0,
      offset = -80,
      type = 16
    },
    {
      value = 99999.01234567,
      offset = -48,
      type = 16
    },
    {
      value = 0,
      offset = -32,
      type = 16
    },
    {
      value = 0,
      offset = -24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Grenade Launcher ] Active ✅"
    },
    {value = 400, type = 16},
    {
      lv = 24,
      offset = -188,
      type = 16
    },
    {
      lv = 24,
      offset = -184,
      type = 16
    },
    {
      lv = 24,
      offset = -180,
      type = 16
    },
    {
      lv = 35,
      offset = -164,
      type = 16
    },
    {
      lv = 4,
      offset = -76,
      type = 16
    },
    {
      lv = 4,
      offset = -72,
      type = 16
    },
    {
      lv = 25,
      offset = -40,
      type = 16
    },
    {
      lv = 20,
      offset = -24,
      type = 16
    },
    {
      lv = 10,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -188,
      type = 16
    },
    {
      value = 0,
      offset = -184,
      type = 16
    },
    {
      value = 0,
      offset = -180,
      type = 16
    },
    {
      value = 0,
      offset = -164,
      type = 16
    },
    {
      value = 0,
      offset = -76,
      type = 16
    },
    {
      value = 0,
      offset = -72,
      type = 16
    },
    {
      value = 99999,
      offset = -40,
      type = 16
    },
    {
      value = 0,
      offset = -24,
      type = 16
    },
    {
      value = 0,
      offset = -12,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Simple Shotgun ] Active ✅"
    },
    {value = 45, type = 16},
    {
      lv = "3.0",
      offset = 12,
      type = 16
    },
    {
      lv = "60.0",
      offset = 28,
      type = 16
    },
    {
      lv = "300.0",
      offset = 148,
      type = 16
    },
    {
      lv = "13.0",
      offset = 164,
      type = 16
    },
    {
      lv = "8.0",
      offset = 192,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 12,
      type = 16
    },
    {
      value = 0,
      offset = 28,
      type = 16
    },
    {
      value = 99999.011,
      offset = 148,
      type = 16
    },
    {
      value = 0,
      offset = 164,
      type = 16
    },
    {
      value = 0,
      offset = 192,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Double Shotgun ] Active ✅"
    },
    {value = 45, type = 16},
    {
      lv = "3.0",
      offset = 12,
      type = 16
    },
    {
      lv = "60.0",
      offset = 28,
      type = 16
    },
    {
      lv = "300.0",
      offset = 148,
      type = 16
    },
    {
      lv = "15.0",
      offset = 164,
      type = 16
    },
    {
      lv = "8.0",
      offset = 192,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 12,
      type = 16
    },
    {
      value = 0,
      offset = 28,
      type = 16
    },
    {
      value = 99999.012,
      offset = 148,
      type = 16
    },
    {
      value = 0,
      offset = 164,
      type = 16
    },
    {
      value = 0,
      offset = 192,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("40.0123456789", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("99999.01234567", gg.REGION_C_BSS)
  gg.clearResults()
end

function snipe()
  qmnb = {
    {memory = 32},
    {
      name = "[ SniperM24 ] Active ✅"
    },
    {value = 912, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ SniperK31 ] Active ✅"
    },
    {value = 720, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Mini-14 ] Active ✅"
    },
    {value = 830, type = 16},
    {
      lv = 13,
      offset = -148,
      type = 16
    },
    {
      lv = 33,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 6,
      offset = -136,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Semi ] Active ✅"
    },
    {value = 710, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 35,
      offset = -144,
      type = 16
    },
    {
      lv = 55,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function bed()
  F = gg.alert(" Anten Bed", "ON", "OFF")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.20930966735", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("999.001234556", gg.REGION_C_BSS)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.25884836912", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("999.001234557", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("999.001234556", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.20930966735", gg.REGION_C_BSS)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("999.001234557", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.25884836912", gg.TYPE_FLOAT)
    gg.clearResults()
  end
end

function ore()
  F = gg.alert(" Anten Quặng", "ON", "OFF")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("1.54026591778", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("999.0012345", gg.REGION_C_BSS)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("1.59360003471", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("999.00123456", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("999.0012345", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("1.54026591778", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("999.00123456", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("1.59360003471", gg.TYPE_FLOAT)
  end
end

function loot()
  F = gg.alert(" Anten Loot", "ON", "OFF")
  if F == 1 then
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.19091719389", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("9999.0001234566", gg.TYPE_FLOAT)
    gg.clearResults()
  elseif F == 2 then
    gg.getResults(999)
    gg.editAll("1.54026591778", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("9999.0001234566", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.19091719389", gg.TYPE_FLOAT)
  end
end

function time()
  F = gg.alert(" V1 V2 Need to adjust low graphics", "V2", "OFF", "V1")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("2.37555122375", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.0000001234", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("3.96402846e-29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.000000123", 16)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.00000121", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("2.37554955482", 16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.00000122", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("3.94430543e-29", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.0000001234", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("2.37555122375", 16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.000000123", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("3.96402846e-29", 16)
  elseif F == 3 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("2.37554955482", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.00000121", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("3.94430543e-29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.00000122", 16)
    gg.clearResults()
  end
end

function xc2()
  F = gg.alert("Adjust To Bright Sky And Lock Time", "Lock-Time", "OFF", "Day-Night+LockTime")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {
        name = "ON Lock Time"
      },
      {value = 1.0600871291899239E-8, type = 16},
      {
        lv = 8.968310171678829E-44,
        offset = -12,
        type = 16
      },
      {
        lv = 6.1124763362074925E32,
        offset = -4,
        type = 16
      },
      {
        lv = 1.0600871291899239E-8,
        offset = 4,
        type = 16
      },
      {
        lv = 1.1210387714598537E-44,
        offset = 52,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = 60,
        type = 16
      }
    }
    qmxg = {
      {
        value = 9.21942286E-41,
        offset = 28,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 1.0600871291899239E-8, type = 16},
      {
        lv = 8.968310171678829E-44,
        offset = -12,
        type = 16
      },
      {
        lv = 6.1124763362074925E32,
        offset = -4,
        type = 16
      },
      {
        lv = 1.0600871291899239E-8,
        offset = 4,
        type = 16
      },
      {
        lv = 1.1210387714598537E-44,
        offset = 52,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = 60,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0.0066999997943639755,
        offset = 28,
        type = 16
      },
      {
        value = 9.219422856485836E-41,
        offset = 36,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 3 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 1.0600871291899239E-8, type = 16},
      {
        lv = 8.968310171678829E-44,
        offset = -12,
        type = 16
      },
      {
        lv = 6.1124763362074925E32,
        offset = -4,
        type = 16
      },
      {
        lv = 1.0600871291899239E-8,
        offset = 4,
        type = 16
      },
      {
        lv = 1.1210387714598537E-44,
        offset = 52,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = 60,
        type = 16
      }
    }
    qmxg = {
      {
        value = 9.21942286E-41,
        offset = 28,
        type = 16
      },
      {
        value = 999,
        offset = 36,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function nuoc()
  F = gg.alert(" Đi Dưới Nước", "MapNew", "OFF", "MapOld")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = 0,
        offset = -36,
        type = 16
      },
      {
        lv = 0,
        offset = -32,
        type = 16
      },
      {
        lv = 1,
        offset = -28,
        type = 16
      },
      {
        lv = 0,
        offset = -24,
        type = 16
      },
      {
        lv = 0,
        offset = -16,
        type = 16
      },
      {
        lv = 0,
        offset = -12,
        type = 16
      }
    }
    qmxg = {
      {
        value = -40,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("0.000123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("10000.001953125", 16)
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = 1.401298464324817E-45,
        offset = -44,
        type = 16
      },
      {
        lv = 0,
        offset = -40,
        type = 16
      },
      {
        lv = 0,
        offset = -36,
        type = 16
      },
      {
        lv = 0,
        offset = -32,
        type = 16
      },
      {
        lv = 1,
        offset = -28,
        type = 16
      },
      {
        lv = 0,
        offset = -24,
        type = 16
      },
      {
        lv = 0,
        offset = -16,
        type = 16
      },
      {
        lv = 0,
        offset = -12,
        type = 16
      }
    }
    qmxg = {
      {
        value = 10,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 3 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("10000.001953125", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.000123456789", 16)
  end
end

function nha()
  F = gg.alert(" V1 Need to adjust high and low graphics ", "V2", "OFF", "V1")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.81399995089", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("0.81399995089", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("5.123456789", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("ON")
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.81399995089", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("0.81399995089", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("5.123456789", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("ON")
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.00012345", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("3.21460819e-29", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.000123456", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("3.25405304e-29", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.0001234567", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("2.37555098534", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("5.123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("5.123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("0.81399995089", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("OFF")
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("5.123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("5.123456789", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("0.81399995089", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("OFF")
    gg.clearResults()
  elseif F == 3 then
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("3.21460819e-29", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.00012345", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("3.25405304e-29", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.000123456", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("ON")
  end
end

function map()
  F = gg.alert("Remove Map", "MapNew", "OFF", "MapOld")
  if F == 1 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 8000, type = 4},
      {
        lv = 100,
        offset = 8,
        type = 4
      },
      {
        lv = 10000,
        offset = 12,
        type = 4
      }
    }
    qmxg = {
      {
        value = 500,
        offset = 12,
        type = 4
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 10000, type = 4},
      {
        lv = 100,
        offset = -4,
        type = 4
      },
      {
        lv = 500,
        offset = 4,
        type = 4
      }
    }
    qmxg = {
      {
        value = 5000,
        offset = 4,
        type = 4
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 8000, type = 4},
      {
        lv = 100,
        offset = 8,
        type = 4
      },
      {
        lv = 500,
        offset = 12,
        type = 4
      }
    }
    qmxg = {
      {
        value = 10000,
        offset = 12,
        type = 4
      }
    }
    xqmnb(qmnb)
  elseif F == 3 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 10000, type = 4},
      {
        lv = 100,
        offset = -4,
        type = 4
      },
      {
        lv = 5000,
        offset = 4,
        type = 4
      }
    }
    qmxg = {
      {
        value = 500,
        offset = 4,
        type = 4
      }
    }
    xqmnb(qmnb)
  end
end

function speed()
  F = gg.alert("Speed", "SpeedSwim", "OFF", "SpeedFarm")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("4.90000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14177720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.15777720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("6.30000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("3.100012345", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("4.90000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14177720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.15777720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("6.30000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("3.100012345", 16)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("4.90000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.15777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("3.100012345", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("4.90000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.15777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("3.100012345", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
  elseif F == 3 then
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.15777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("3.100012345", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14177720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14777720249", 16)
    gg.clearList()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("6.30000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("4.90000019073", 16)
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.15777720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("3.100012345", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14177720249", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.14777720249", 16)
    gg.clearList()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("6.30000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("4.90000019073", 16)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 1.233142648605839E-42, type = 16},
      {
        lv = 4,
        offset = 12,
        type = 16
      },
      {
        lv = 7.987401246651457E-43,
        offset = 60,
        type = 16
      }
    }
    qmxg = {
      {
        value = 5.2,
        offset = 12,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 1.233142648605839E-42, type = 16},
      {
        lv = 8,
        offset = 12,
        type = 16
      },
      {
        lv = 7.847271400218976E-43,
        offset = 60,
        type = 16
      }
    }
    qmxg = {
      {
        value = 9.5,
        offset = 12,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function fly()
  F = gg.alert("Fly With Hoo ", "ON", "OFF")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 24008, type = 4},
      {
        lv = 2139095039,
        offset = -20,
        type = 4
      },
      {
        lv = 24008,
        offset = 4,
        type = 4
      },
      {
        lv = 0,
        offset = 20,
        type = 4
      },
      {
        lv = 0,
        offset = 24,
        type = 4
      },
      {
        lv = 1,
        offset = 28,
        type = 4
      },
      {
        lv = 0,
        offset = 32,
        type = 4
      },
      {
        lv = 0,
        offset = 36,
        type = 4
      },
      {
        lv = 0,
        offset = 40,
        type = 4
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 28,
        type = 4
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 24000, type = 4},
      {
        lv = 2139095039,
        offset = -20,
        type = 4
      },
      {
        lv = 24000,
        offset = 4,
        type = 4
      },
      {
        lv = 0,
        offset = 20,
        type = 4
      },
      {
        lv = 0,
        offset = 24,
        type = 4
      },
      {
        lv = 1,
        offset = 28,
        type = 4
      },
      {
        lv = 0,
        offset = 32,
        type = 4
      },
      {
        lv = 0,
        offset = 36,
        type = 4
      },
      {
        lv = 0,
        offset = 40,
        type = 4
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 28,
        type = 4
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 24008, type = 4},
      {
        lv = 2139095039,
        offset = -20,
        type = 4
      },
      {
        lv = 24008,
        offset = 4,
        type = 4
      },
      {
        lv = 0,
        offset = 20,
        type = 4
      },
      {
        lv = 0,
        offset = 24,
        type = 4
      },
      {
        lv = 0,
        offset = 28,
        type = 4
      },
      {
        lv = 0,
        offset = 32,
        type = 4
      },
      {
        lv = 0,
        offset = 36,
        type = 4
      },
      {
        lv = 0,
        offset = 40,
        type = 4
      }
    }
    qmxg = {
      {
        value = 1,
        offset = 28,
        type = 4
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 24000, type = 4},
      {
        lv = 2139095039,
        offset = -20,
        type = 4
      },
      {
        lv = 24000,
        offset = 4,
        type = 4
      },
      {
        lv = 0,
        offset = 20,
        type = 4
      },
      {
        lv = 0,
        offset = 24,
        type = 4
      },
      {
        lv = 0,
        offset = 28,
        type = 4
      },
      {
        lv = 0,
        offset = 32,
        type = 4
      },
      {
        lv = 0,
        offset = 36,
        type = 4
      },
      {
        lv = 0,
        offset = 40,
        type = 4
      }
    }
    qmxg = {
      {
        value = 1,
        offset = 28,
        type = 4
      }
    }
    xqmnb(qmnb)
  end
end

function view()
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("-0.9855342507362366", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("-500", gg.REGION_C_BSS)
  gg.clearResults()
  qmnb = {
    {memory = 1048576},
    {name = "ON"},
    {value = 4.4570662209845934E-29, type = 16},
    {
      lv = 2.2500014305114746,
      offset = 4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 2.26000142097,
      offset = 4,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("1.58116769791", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("-999", gg.REGION_C_BSS)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("0.16947640479", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("-999", gg.REGION_C_BSS)
  gg.clearResults()
  gg.clearResults()
  gg.setRanges(gg.REGION_CODE_SYS)
  gg.searchNumber("-6.171913993364983E27;-1.0061304023208683E28;-1.220370790326068E21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("-1.0061304023208683E28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(9990)
  gg.editAll("10.000123456789", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.clearResults()
  gg.setRanges(16384)
  gg.searchNumber("-6.171913993364983E27;-1.0061304023208683E28;-1.220370790326068E21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("-1.0061304023208683E28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(9990)
  gg.editAll("10.000123456789", gg.TYPE_FLOAT)
  gg.clearResults()
  qmnb = {
    {memory = 16384},
    {name = "ON"},
    {value = 99, type = 16},
    {
      lv = -100,
      offset = 4,
      type = 16
    },
    {
      lv = -180,
      offset = 12,
      type = 16
    },
    {
      lv = 180,
      offset = 16,
      type = 16
    },
    {
      lv = -200,
      offset = 20,
      type = 16
    },
    {
      lv = 200,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 8,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32768},
    {name = "ON"},
    {value = 99, type = 16},
    {
      lv = -100,
      offset = 4,
      type = 16
    },
    {
      lv = -180,
      offset = 12,
      type = 16
    },
    {
      lv = 180,
      offset = 16,
      type = 16
    },
    {
      lv = -200,
      offset = 20,
      type = 16
    },
    {
      lv = 200,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 8,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "50%"},
    {value = 48, type = 16},
    {
      lv = 0,
      offset = 4,
      type = 16
    },
    {
      lv = 0,
      offset = 8,
      type = 16
    },
    {
      lv = 0,
      offset = 12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 10,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "100%"},
    {value = 45, type = 16},
    {
      lv = 0,
      offset = 4,
      type = 16
    },
    {
      lv = 0,
      offset = 8,
      type = 16
    },
    {
      lv = 0,
      offset = 12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 10,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "10% Magic"},
    {value = 0.5400000214576721, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "100% Xong Magic"
    },
    {value = 0.3400000035762787, type = 16},
    {
      lv = 0.10999999940395355,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("5.127597087642792E-29", gg.TYPE_FLOAT)
  gg.getResults(900)
  gg.editAll("5.127597087642792E29", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_CODE_APP)
  gg.searchNumber("0.14177720249", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("0.14777720249", 16)
  gg.clearList()
  gg.clearResults()
  gg.setRanges(gg.REGION_CODE_APP)
  gg.searchNumber("6.30000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("4.90000019073", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_CODE_SYS)
  gg.searchNumber("0.14177720249", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("0.14777720249", 16)
  gg.clearList()
  gg.clearResults()
  gg.setRanges(gg.REGION_CODE_SYS)
  gg.searchNumber("6.30000019073", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("4.90000019073", 16)
  qmnb = {
    {memory = 32},
    {
      name = "[ M4 ] Active ✅"
    },
    {value = 830, type = 16},
    {
      lv = 12,
      offset = -148,
      type = 16
    },
    {
      lv = 24,
      offset = -144,
      type = 16
    },
    {
      lv = 45,
      offset = -140,
      type = 16
    },
    {
      lv = 3.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Smg ] Active ✅"
    },
    {value = 300, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 32,
      offset = -144,
      type = 16
    },
    {
      lv = 44,
      offset = -140,
      type = 16
    },
    {
      lv = 2.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[Akm M762] Active ✅"
    },
    {value = 735, type = 16},
    {
      lv = 50,
      offset = -140,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Qbz ] Active ✅"
    },
    {value = 790, type = 16},
    {
      lv = 12,
      offset = -148,
      type = 16
    },
    {
      lv = 27,
      offset = -144,
      type = 16
    },
    {
      lv = 45,
      offset = -140,
      type = 16
    },
    {
      lv = 3.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Uzi ] Active ✅"
    },
    {value = 320, type = 16},
    {
      lv = 16,
      offset = -148,
      type = 16
    },
    {
      lv = 34,
      offset = -144,
      type = 16
    },
    {
      lv = 42,
      offset = -140,
      type = 16
    },
    {
      lv = 3,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Famas ] Active ✅"
    },
    {value = 360, type = 16},
    {
      lv = 14,
      offset = -148,
      type = 16
    },
    {
      lv = 30,
      offset = -144,
      type = 16
    },
    {
      lv = 42,
      offset = -140,
      type = 16
    },
    {
      lv = 2.5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ M249 ] Active ✅"
    },
    {value = 480, type = 16},
    {
      lv = 20,
      offset = -148,
      type = 16
    },
    {
      lv = 40,
      offset = -144,
      type = 16
    },
    {
      lv = 55,
      offset = -140,
      type = 16
    },
    {
      lv = 10,
      offset = -124,
      type = 16
    },
    {
      lv = 7,
      offset = 16,
      type = 16
    },
    {
      lv = 10,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Lewis ] Active ✅"
    },
    {value = "480.0", type = 16},
    {
      lv = "20.0",
      offset = -148,
      type = 16
    },
    {
      lv = "40.0",
      offset = -144,
      type = 16
    },
    {
      lv = "6.0",
      offset = -136,
      type = 16
    },
    {
      lv = "60.0",
      offset = -120,
      type = 16
    },
    {
      lv = "0.5",
      offset = -100,
      type = 16
    },
    {
      lv = "4.0",
      offset = 16,
      type = 16
    },
    {
      lv = "4.0",
      offset = 24,
      type = 16
    },
    {
      lv = "1.0",
      offset = 160,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 0,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -120,
      type = 16
    },
    {
      value = 0,
      offset = -100,
      type = 16
    },
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    },
    {
      value = 0,
      offset = 160,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  qmnb = {
    {memory = 32},
    {name = "ON"},
    {value = 2.1000001430511475, type = 16},
    {
      lv = 1.233142648605839E-42,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1.5,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("1.23314265e-42;1.9~5.5;7.93134931e-43", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("1.9~5.5", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10000)
  gg.editAll("0.0000001", 16)
  gg.toast("50%")
  gg.clearResults()
  qmnb = {
    {memory = 32},
    {
      name = "100% Done Fast Changed"
    },
    {value = 2.83333349228, type = 16},
    {
      lv = 1.233142648605839E-42,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1.0E-7,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  qmnb = {
    {memory = 32},
    {
      name = "[ Bazoka ] Active ✅"
    },
    {value = 278, type = 16},
    {
      lv = 15,
      offset = -196,
      type = 16
    },
    {
      lv = 30,
      offset = -192,
      type = 16
    },
    {
      lv = 45,
      offset = -188,
      type = 16
    },
    {
      lv = 35,
      offset = -172,
      type = 16
    },
    {
      lv = 4,
      offset = -84,
      type = 16
    },
    {
      lv = 4,
      offset = -80,
      type = 16
    },
    {
      lv = 40,
      offset = -48,
      type = 16
    },
    {
      lv = 20,
      offset = -32,
      type = 16
    },
    {
      lv = 10,
      offset = -24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -196,
      type = 16
    },
    {
      value = 0,
      offset = -192,
      type = 16
    },
    {
      value = 0,
      offset = -188,
      type = 16
    },
    {
      value = 0,
      offset = -172,
      type = 16
    },
    {
      value = 0,
      offset = -84,
      type = 16
    },
    {
      value = 0,
      offset = -80,
      type = 16
    },
    {
      value = 99999,
      offset = -48,
      type = 16
    },
    {
      value = 0,
      offset = -32,
      type = 16
    },
    {
      value = 0,
      offset = -24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Grenade Launcher ] Active ✅"
    },
    {value = 400, type = 16},
    {
      lv = 24,
      offset = -188,
      type = 16
    },
    {
      lv = 24,
      offset = -184,
      type = 16
    },
    {
      lv = 24,
      offset = -180,
      type = 16
    },
    {
      lv = 35,
      offset = -164,
      type = 16
    },
    {
      lv = 4,
      offset = -76,
      type = 16
    },
    {
      lv = 4,
      offset = -72,
      type = 16
    },
    {
      lv = 25,
      offset = -40,
      type = 16
    },
    {
      lv = 20,
      offset = -24,
      type = 16
    },
    {
      lv = 10,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 0,
      offset = -188,
      type = 16
    },
    {
      value = 0,
      offset = -184,
      type = 16
    },
    {
      value = 0,
      offset = -180,
      type = 16
    },
    {
      value = 0,
      offset = -164,
      type = 16
    },
    {
      value = 0,
      offset = -76,
      type = 16
    },
    {
      value = 0,
      offset = -72,
      type = 16
    },
    {
      value = 99999,
      offset = -40,
      type = 16
    },
    {
      value = 0,
      offset = -24,
      type = 16
    },
    {
      value = 0,
      offset = -12,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Semi ] Active ✅"
    },
    {value = 710, type = 16},
    {
      lv = 15,
      offset = -148,
      type = 16
    },
    {
      lv = 35,
      offset = -144,
      type = 16
    },
    {
      lv = 55,
      offset = -140,
      type = 16
    },
    {
      lv = 5,
      offset = -124,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "[ Mini-14 ] Active ✅"
    },
    {value = 830, type = 16},
    {
      lv = 13,
      offset = -148,
      type = 16
    },
    {
      lv = 33,
      offset = -144,
      type = 16
    },
    {
      lv = 50,
      offset = -140,
      type = 16
    },
    {
      lv = 6,
      offset = -136,
      type = 16
    },
    {
      lv = 4,
      offset = 16,
      type = 16
    },
    {
      lv = 4,
      offset = 24,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99999,
      offset = 0,
      type = 16
    },
    {
      value = 0,
      offset = -148,
      type = 16
    },
    {
      value = 0,
      offset = -144,
      type = 16
    },
    {
      value = 0,
      offset = -140,
      type = 16
    },
    {
      value = 1,
      offset = -136,
      type = 16
    },
    {
      value = 0,
      offset = -124,
      type = 16
    },
    {
      value = 0,
      offset = 16,
      type = 16
    },
    {
      value = 0,
      offset = 24,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "ON"},
    {value = 24008, type = 4},
    {
      lv = 2139095039,
      offset = -20,
      type = 4
    },
    {
      lv = 24008,
      offset = 4,
      type = 4
    },
    {
      lv = 0,
      offset = 20,
      type = 4
    },
    {
      lv = 0,
      offset = 24,
      type = 4
    },
    {
      lv = 1,
      offset = 28,
      type = 4
    },
    {
      lv = 0,
      offset = 32,
      type = 4
    },
    {
      lv = 0,
      offset = 36,
      type = 4
    },
    {
      lv = 0,
      offset = 40,
      type = 4
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 28,
      type = 4
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "ON"},
    {value = 24000, type = 4},
    {
      lv = 2139095039,
      offset = -20,
      type = 4
    },
    {
      lv = 24000,
      offset = 4,
      type = 4
    },
    {
      lv = 0,
      offset = 20,
      type = 4
    },
    {
      lv = 0,
      offset = 24,
      type = 4
    },
    {
      lv = 1,
      offset = 28,
      type = 4
    },
    {
      lv = 0,
      offset = 32,
      type = 4
    },
    {
      lv = 0,
      offset = 36,
      type = 4
    },
    {
      lv = 0,
      offset = 40,
      type = 4
    }
  }
  qmxg = {
    {
      value = 0,
      offset = 28,
      type = 4
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "ON"},
    {value = 1.233142648605839E-42, type = 16},
    {
      lv = 4,
      offset = 12,
      type = 16
    },
    {
      lv = 7.987401246651457E-43,
      offset = 60,
      type = 16
    }
  }
  qmxg = {
    {
      value = 5.2,
      offset = 12,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "30% Magic"},
    {value = 0.6899999976158142, type = 16},
    {
      lv = 0.1599999964237213,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "60% Magic"},
    {value = 0.47999998927116394, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "80% Magic"},
    {value = 0.44999998807907104, type = 16},
    {
      lv = 0.03999999910593033,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 8,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {
      name = "✅OneClick"
    },
    {value = 1.233142648605839E-42, type = 16},
    {
      lv = 8,
      offset = 12,
      type = 16
    },
    {
      lv = 7.847271400218976E-43,
      offset = 60,
      type = 16
    }
  }
  qmxg = {
    {
      value = 9.5,
      offset = 12,
      type = 16
    }
  }
  xqmnb(qmnb)
end

function fast()
  gg.clearResults()
  qmnb = {
    {memory = 32},
    {name = "ON"},
    {value = 2.1000001430511475, type = 16},
    {
      lv = 1.233142648605839E-42,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1.5,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("1.23314265e-42;1.9~5.5;7.93134931e-43", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("1.9~5.5", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10000)
  gg.editAll("0.0000001", 16)
  gg.toast("50%")
  gg.clearResults()
  qmnb = {
    {memory = 32},
    {
      name = "100% Done Fast Changed"
    },
    {value = 2.83333349228, type = 16},
    {
      lv = 1.233142648605839E-42,
      offset = -12,
      type = 16
    }
  }
  qmxg = {
    {
      value = 1.0E-7,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg.clearResults()
end

function shot()
  F = gg.alert("Fast Shot ", "X8", "OFF", "X4")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00005120005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00005120005", 16)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
  elseif F == 3 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00061000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00061000005", 16)
  end
end

function anti()
  F = gg.alert("Anti Boss Ko cần out sever ( Anti Turret Chỉ Hiệu Quả Khi Không Có Người Ởi Gần Mở Xong Out Sever Vô Lại )", "ON", "OFF")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00005120005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("2.51061000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("0.00100000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("2.51061000005", 16)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber("2.51061000005", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("0.00100000005", 16)
  end
end

function moto()
  menu1 = gg.choice({
    "⭐[Motorcycle]",
    "⭐[Chariot Cars 4 Wheel]",
    "⭐[Boat]",
    "⭐[Jeep]",
    "⭐[Cow car]",
    "⭐[Steel Burst]",
    "⭐[Vepa]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Unlock Speed Car Menu]")
  if menu1 == 1 then
    motor()
  end
  if menu1 == 2 then
    cus()
  end
  if menu1 == 3 then
    boat()
  end
  if menu1 == 4 then
    car()
  end
  if menu1 == 5 then
    cow()
  end
  if menu1 == 6 then
    steel()
  end
  if menu1 == 7 then
    vepa()
  end
  if menu1 == 8 then
    C()
  end
  GLWW = -1
end

function motor()
  Q = gg.prompt({
    " Setting Speed Km/h: [60;120] "
  }, {90}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 4000, type = 16},
      {
        lv = 30,
        offset = -12,
        type = 16
      },
      {
        lv = 60,
        offset = -8,
        type = 16
      },
      {
        lv = 1000,
        offset = -4,
        type = 16
      },
      {
        lv = 80,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function cus()
  Q = gg.prompt({
    " Setting Speed Km/h: [60;120] "
  }, {90}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 7000, type = 16},
      {
        lv = 270,
        offset = -8,
        type = 16
      },
      {
        lv = 2700,
        offset = -4,
        type = 16
      },
      {
        lv = 30,
        offset = 44,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 36,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function boat()
  Q = gg.prompt({
    " Setting Speed Km/h: [40;70] "
  }, {70}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.299999952316284, type = 16},
      {
        lv = 0.800000011920929,
        offset = -4,
        type = 16
      },
      {
        lv = 0.6000000238418579,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 72,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function car()
  Q = gg.prompt({
    " Setting Speed Km/h: [75;120] "
  }, {90}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 7000, type = 16},
      {
        lv = 90,
        offset = 40,
        type = 16
      },
      {
        lv = 45,
        offset = 44,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 36,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function cow()
  Q = gg.prompt({
    " Setting Speed Km/h: [80;120] "
  }, {90}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 7000, type = 16},
      {
        lv = 110,
        offset = 40,
        type = 16
      },
      {
        lv = 45,
        offset = 44,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 36,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function steel()
  Q = gg.prompt({
    " Setting Speed Km/h: [80;120] "
  }, {90}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 7000, type = 16},
      {
        lv = 100,
        offset = 40,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 36,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function vepa()
  Q = gg.prompt({
    " Setting Speed Km/h: [30;120] "
  }, {90}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 4800, type = 16},
      {
        lv = 1200,
        offset = -4,
        type = 16
      },
      {
        lv = 40,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function st()
  F = gg.alert("Đi Xuyên Đá Khu", "ON", "OFF")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "50%"},
      {value = 6.699999809265137, type = 16},
      {
        lv = 0.10000000149011612,
        offset = 16,
        type = 16
      },
      {
        lv = 0.10000000149011612,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = -999,
        offset = 16,
        type = 16
      },
      {
        value = -999,
        offset = 24,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "100%"},
      {value = 999, type = 16},
      {
        lv = 0.10000000149011612,
        offset = 16,
        type = 16
      },
      {
        lv = 0.004999999888241291,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 8.88479995728,
        offset = 20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 32},
      {name = "100%"},
      {value = 999, type = 16},
      {
        lv = 0.10000000149011612,
        offset = 16,
        type = 16
      },
      {
        lv = 0.004999999888241291,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 1.00000003E32,
        offset = 20,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function boi()
  menu1 = gg.choice({
    "⭐[Map Old]",
    "⭐[Map New]",
    "ʙᴀᴄᴋ ᴛᴏ ᴍᴇɴᴜ"
  }, nil, "[Swimming in the Sky]")
  if menu1 == 1 then
    old()
  end
  if menu1 == 2 then
    new()
  end
  if menu1 == 3 then
    index()
  end
  GLWW = -1
end

function old()
  Q = gg.prompt({
    " Độ Cao : [10;400] "
  }, {10}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 100,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 100,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = -4900, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = 152,
        type = 16
      },
      {
        lv = 2.755148962647596E-40,
        offset = 200,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = 180,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function new()
  Q = gg.prompt({
    " Độ Cao : [10;400] "
  }, {10}, {"number"})
  if Q == nil then
    return
  else
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 100,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 100,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = 0,
        offset = -36,
        type = 16
      },
      {
        lv = 0,
        offset = -32,
        type = 16
      },
      {
        lv = 1,
        offset = -28,
        type = 16
      },
      {
        lv = 0,
        offset = -24,
        type = 16
      },
      {
        lv = 0,
        offset = -16,
        type = 16
      },
      {
        lv = 0,
        offset = -12,
        type = 16
      }
    }
    qmxg = {
      {
        value = Q[1],
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function view2()
  F = gg.alert("👁️ iPad View", "ON", "OFF")
  if F == 1 then
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = -1.6542215634762601E38, type = 16},
      {
        lv = 3.1415927410125732,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = 280,
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = -1.6542215634762601E38, type = 16},
      {
        lv = 3.1415927410125732,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = 280,
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 32768},
      {name = "OFF"},
      {value = -1.6542215634762601E38, type = 16},
      {
        lv = 3.1415927410125732,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = 360,
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 16384},
      {name = "OFF"},
      {value = -1.6542215634762601E38, type = 16},
      {
        lv = 3.1415927410125732,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = 360,
        offset = 4,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function shoot()
  F = gg.alert("💥Bazoka Bắn Xuyên Nhà", "100%", "OFF", "50%")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("3.700001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("3.700001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("-0.00001", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("5.600001234567", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("-0.00001", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("5.600001234567", 16)
    gg.toast("ON")
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("5.600001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("5.600001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("3.700001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("3.700001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.toast("OFF")
  elseif F == 3 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("5.600001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("5.600001234567", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-0.00001", 16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("-0.00001", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("3.700001234567", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("-0.00001", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("3.700001234567", 16)
    gg.toast("ON")
  end
end

function soul()
  F = gg.alert("👻Leaving the Soul", "ON", "OFF")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.125", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("2.000123456789", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.125", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("2.000123456789", 16)
    gg.toast("ON")
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("2.000123456789", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.125", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("2.000123456789", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("0.125", 16)
    gg.toast("OFF")
  end
end

function jump()
  F = gg.alert("🦘Long Jump", "ON", "OFF")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("40", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-10.0123456789", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("40", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("-10.0123456789", 16)
    gg.toast("ON")
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("-10.0123456789", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("40", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("-10.0123456789", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("40", 16)
    gg.toast("OFF")
  end
end

function build()
  F = gg.alert("🧱Forced Construction", "ON", "OFF")
  if F == 1 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 2, type = 16},
      {
        lv = -2,
        offset = 4,
        type = 16
      },
      {
        lv = 2,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = 1.96,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 2, type = 16},
      {
        lv = -2,
        offset = 4,
        type = 16
      },
      {
        lv = 2,
        offset = 8,
        type = 16
      }
    }
    qmxg = {
      {
        value = 1.96,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 10000, type = 4},
      {
        lv = 100,
        offset = -4,
        type = 4
      },
      {
        lv = 5000,
        offset = 4,
        type = 4
      }
    }
    qmxg = {
      {
        value = 500,
        offset = 4,
        type = 4
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "ON"},
      {value = 10000, type = 4},
      {
        lv = 100,
        offset = -4,
        type = 4
      },
      {
        lv = 500,
        offset = 4,
        type = 4
      }
    }
    qmxg = {
      {
        value = 5000,
        offset = 4,
        type = 4
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("1.96", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("2", 16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("1.96", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(300)
    gg.editAll("2", 16)
    gg.toast("OFF")
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 10000, type = 4},
      {
        lv = 100,
        offset = -4,
        type = 4
      },
      {
        lv = 5000,
        offset = 4,
        type = 4
      }
    }
    qmxg = {
      {
        value = 500,
        offset = 4,
        type = 4
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32},
      {name = "OFF"},
      {value = 10000, type = 4},
      {
        lv = 100,
        offset = -4,
        type = 4
      },
      {
        lv = 500,
        offset = 4,
        type = 4
      }
    }
    qmxg = {
      {
        value = 5000,
        offset = 4,
        type = 4
      }
    }
    xqmnb(qmnb)
  end
end

function antidead()
  F = gg.alert("💉Anti dead Fly Remove map", "ON", "OFF")
  if F == 1 then
    qmnb = {
      {memory = 16384},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "ON"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 0,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {memory = 16384},
      {name = "OFF"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 100,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {memory = 32768},
      {name = "OFF"},
      {value = 99, type = 16},
      {
        lv = -100,
        offset = 4,
        type = 16
      },
      {
        lv = -180,
        offset = 12,
        type = 16
      },
      {
        lv = 180,
        offset = 16,
        type = 16
      },
      {
        lv = -200,
        offset = 20,
        type = 16
      },
      {
        lv = 200,
        offset = 24,
        type = 16
      }
    }
    qmxg = {
      {
        value = 100,
        offset = 8,
        type = 16
      }
    }
    xqmnb(qmnb)
  end
end

function Ext()
  print("🤣Parlraj madrchod Tara Baap🤣")
  gg.clearList()
  os.exit()
end






while true do
  menuend = 0
  if gg.isVisible(true) then
    gg.setVisible(false)
    menuend = 1
    if menuend == 1 then
      Hh()
    end
  end
end
