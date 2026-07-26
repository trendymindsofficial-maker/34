'use client';
import dynamic from 'next/dynamic';

const App = dynamic(() => import('../App'), {
  ssr: false,
  loading: () => (
    <div className="min-h-screen bg-[#080808] text-white flex items-center justify-center">
      <div className="text-amber-400 font-bold text-sm animate-pulse">
        Loading SPC Student Privilege Card...
      </div>
    </div>
  ),
});

export default function Page() {
  return <App />;
}
