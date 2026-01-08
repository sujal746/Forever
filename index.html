import React, { useState, useEffect } from 'react';
import { Heart, Mail, Sparkles, Stars, Gift, Flower2, ChevronRight, Utensils, Camera, Map, Moon } from 'lucide-react';

const App = () => {
  const [stage, setStage] = useState('closed'); // 'closed', 'reasons', 'proposing', 'accepted'
  const [reasonIndex, setReasonIndex] = useState(0);
  const [noCount, setNoCount] = useState(0);
  const [noButtonPos, setNoButtonPos] = useState({ x: 0, y: 0 });
  const [isNoMoving, setIsNoMoving] = useState(false);

  const reasons = [
    { text: "I love your beautiful smile that lights up my whole world...", icon: <Sparkles className="text-yellow-400" /> },
    { text: "I love how you always know exactly how to make me laugh...", icon: <Gift className="text-purple-400" /> },
    { text: "I love all the little adventures we've been on together...", icon: <Map className="text-green-400" /> },
    { text: "And most of all, I love how you make me a better person every day.", icon: <Heart className="text-red-500" fill="currentColor" /> }
  ];

  const noMessages = [
    "No 🥺", "Are you sure? 💔", "Pwease? 👉👈", "Really? 😢", "Think again! 🧸", 
    "I'll be sad... 😿", "Don't do this! 🛑", "Wait! 🖐️", "Click Yes! ✨", "Give me a chance! 🎀"
  ];

  const handleNoInteraction = () => {
    setNoCount(prev => prev + 1);
    const padding = 100;
    const x = Math.random() * (window.innerWidth - padding * 2) + padding;
    const y = Math.random() * (window.innerHeight - padding * 2) + padding;
    setNoButtonPos({ x, y });
    setIsNoMoving(true);
  };

  const nextReason = () => {
    if (reasonIndex < reasons.length - 1) {
      setReasonIndex(prev => prev + 1);
    } else {
      setStage('proposing');
    }
  };

  // Falling elements logic
  const renderFloatingItems = () => {
    return Array.from({ length: 20 }).map((_, i) => (
      <div
        key={i}
        className="fixed pointer-events-none animate-bounce opacity-30 text-2xl"
        style={{
          left: `${Math.random() * 100}vw`,
          top: `-10vh`,
          animationDuration: `${Math.random() * 3 + 4}s`,
          animationDelay: `${Math.random() * 5}s`,
          transform: `rotate(${Math.random() * 360}deg)`,
          animationIterationCount: 'infinite',
          animationTimingFunction: 'linear'
        }}
      >
        {['🌸', '💖', '✨', '🎀', '🧸'][Math.floor(Math.random() * 5)]}
      </div>
    ));
  };

  return (
    <div className="min-h-screen bg-[#fff5f8] flex flex-col items-center justify-center overflow-hidden font-sans p-6 relative">
      {renderFloatingItems()}
      
      {/* Stage 1: The Sealed Letter */}
      {stage === 'closed' && (
        <div className="flex flex-col items-center animate-in zoom-in duration-700">
          <div 
            onClick={() => setStage('reasons')}
            className="group cursor-pointer bg-white p-16 rounded-[3rem] shadow-[0_20px_50px_rgba(255,182,193,0.4)] transition-all hover:scale-105 active:scale-95 relative border-4 border-pink-100"
          >
            <div className="absolute -top-6 -right-6 bg-pink-500 text-white p-4 rounded-full animate-bounce shadow-lg">
              <Mail size={32} />
            </div>
            <div className="flex flex-col items-center gap-4">
              <div className="w-24 h-24 bg-pink-50 rounded-full flex items-center justify-center group-hover:bg-pink-100 transition-colors">
                <Heart size={48} className="text-pink-500 group-hover:scale-110 transition-transform" />
              </div>
              <p className="text-2xl font-bold text-pink-600 italic">For Someone Special</p>
            </div>
          </div>
          <p className="mt-10 text-pink-400 font-medium tracking-widest animate-pulse">TAP TO OPEN</p>
        </div>
      )}

      {/* Stage 2: Reasons Slideshow */}
      {stage === 'reasons' && (
        <div className="max-w-md w-full bg-white rounded-[2.5rem] shadow-2xl p-10 text-center relative z-10 animate-in fade-in slide-in-from-right-10">
          <div className="flex justify-center mb-8">
            <div className="p-5 bg-pink-50 rounded-2xl animate-spin-slow">
              {reasons[reasonIndex].icon}
            </div>
          </div>
          <p className="text-2xl font-medium text-gray-700 leading-relaxed mb-10 h-32 flex items-center justify-center">
            "{reasons[reasonIndex].text}"
          </p>
          <button
            onClick={nextReason}
            className="w-full bg-pink-500 hover:bg-pink-600 text-white py-4 rounded-2xl text-xl font-bold shadow-lg transition-all flex items-center justify-center gap-2 group"
          >
            {reasonIndex === reasons.length - 1 ? "I have a question..." : "Next Reason"}
            <ChevronRight className="group-hover:translate-x-1 transition-transform" />
          </button>
          <div className="mt-6 flex justify-center gap-2">
            {reasons.map((_, i) => (
              <div key={i} className={`h-2 rounded-full transition-all ${i === reasonIndex ? 'w-8 bg-pink-500' : 'w-2 bg-pink-100'}`} />
            ))}
          </div>
        </div>
      )}

      {/* Stage 3: The Big Question */}
      {stage === 'proposing' && (
        <div className="max-w-md w-full bg-white rounded-[3rem] shadow-[0_25px_60px_rgba(255,77,109,0.2)] p-10 text-center relative z-10 animate-in zoom-in duration-500 border-b-8 border-pink-500">
          <div className="flex justify-center mb-6">
            <div className="relative">
              <Heart size={100} fill="#ff4d6d" color="#ff4d6d" className="animate-pulse" />
              <div className="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 text-white">
                <Flower2 size={40} />
              </div>
            </div>
          </div>
          
          <h1 className="text-3xl font-black text-gray-800 mb-6 italic">
            So, my dearest...
          </h1>
          
          <p className="text-4xl font-black text-pink-500 mb-12 leading-tight">
            Will you be my <span className="underline decoration-wavy decoration-yellow-300">Forever?</span> 💍
          </p>

          <div className="flex flex-col sm:flex-row items-center justify-center gap-6 min-h-[80px]">
            <button
              onClick={() => setStage('accepted')}
              className="bg-pink-500 hover:bg-pink-600 text-white px-12 py-5 rounded-full text-2xl font-black shadow-[0_10px_20px_rgba(236,72,153,0.3)] transition-all hover:scale-110 active:scale-95 flex items-center gap-3 order-1"
            >
              YES! <Heart fill="white" size={24} />
            </button>

            <button
              onMouseEnter={handleNoInteraction}
              onClick={handleNoInteraction}
              style={isNoMoving ? {
                position: 'fixed',
                left: `${noButtonPos.x}px`,
                top: `${noButtonPos.y}px`,
                zIndex: 100,
                transform: `scale(${Math.max(0.5, 1 - noCount * 0.05)})`,
                opacity: Math.max(0.3, 1 - noCount * 0.1)
              } : {}}
              className="bg-gray-100 text-gray-400 px-8 py-4 rounded-full text-lg font-bold transition-all order-2"
            >
              {noMessages[Math.min(noCount, noMessages.length - 1)]}
            </button>
          </div>
        </div>
      )}

      {/* Stage 4: Celebration */}
      {stage === 'accepted' && (
        <div className="fixed inset-0 z-50 flex items-center justify-center bg-[#fff0f3] animate-in fade-in duration-1000">
          <div className="absolute inset-0 overflow-hidden pointer-events-none">
            {Array.from({ length: 40 }).map((_, i) => (
              <div
                key={i}
                className="absolute animate-bounce"
                style={{
                  left: `${Math.random() * 100}%`,
                  top: `${Math.random() * 100}%`,
                  animationDelay: `${Math.random() * 2}s`,
                  fontSize: `${Math.random() * 20 + 20}px`
                }}
              >
                {['💖', '🌸', '✨', '🦋', '🍭'][Math.floor(Math.random() * 5)]}
              </div>
            ))}
          </div>
          
          <div className="text-center p-10 max-w-xl relative z-10 bg-white/80 backdrop-blur-md rounded-[4rem] shadow-2xl border-4 border-white">
            <div className="mb-8 flex justify-center gap-4">
              <Stars className="text-yellow-400 animate-pulse" size={60} />
              <div className="relative">
                <Heart size={140} fill="#ff4d6d" color="#ff4d6d" className="animate-bounce" />
                <span className="absolute inset-0 flex items-center justify-center text-5xl">🧸</span>
              </div>
              <Stars className="text-yellow-400 animate-pulse" size={60} />
            </div>

            <h1 className="text-7xl font-black text-pink-600 mb-6 tracking-tighter">
              OMG YESSS! 🎉
            </h1>
            
            <div className="space-y-6">
              <p className="text-3xl text-pink-500 font-bold italic">
                I'm the luckiest person in the world! 🌎✨
              </p>
              <p className="text-gray-600 text-xl font-medium">
                I promise to love you, cherish you, and share all my snacks with you forever.
              </p>
            </div>

            <div className="mt-12 py-6 px-10 bg-pink-500 rounded-3xl shadow-xl inline-block rotate-2">
              <p className="text-white font-bold text-2xl tracking-widest">
                YOU & ME FOREVER ❤️
              </p>
            </div>
            
            <p className="mt-12 text-pink-200 text-sm italic">You can close this now, but my love won't end!</p>
          </div>
        </div>
      )}

      <style dangerouslySetInnerHTML={{ __html: `
        @keyframes spin-slow {
          from { transform: rotate(0deg); }
          to { transform: rotate(360deg); }
        }
        .animate-spin-slow {
          animation: spin-slow 8s linear infinite;
        }
      `}} />
    </div>
  );
};

export default App;
